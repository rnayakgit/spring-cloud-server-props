<block>
application.yaml 
server:
  port: 8090
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/rnayakgit/spring-cloud-server-props.git ## ti fetchs details from git.
         collects properties details from application.yaml file like Profiles isn Spring boot.

        health:
          enabled: true
      name: springcloudclientconfig

management:
  endpoint:
    health:
      show-details: always
      
      
      
      url to Provide to fetch details from <applicationname>.properties file
      
      http://localhost:8090/SpringCloudConfigApplication/prod
      http://localhost:8090/SpringCloudConfigApplication/dafualt
      
      </block>
