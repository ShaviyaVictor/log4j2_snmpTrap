# log4j-log4j2_migration_template
**Log4j Migration Update: Use Parent POM Versioning (Selfcare Service)**      
My custom template for setting up my projects, Template project for Log4j migration to Log4j 2 in Spring Boot(Java).           
Together with resources in the README file.           
As a developer
I want to migrate Selfcare Service (SIF) to 2.17.2 of log4j 2
So that vulnerabilities can be mitigated.

###### Acceptance Criteria
- Current information logged from application should maintain the exact format in place currently
    - Details need to remain the same so upgrade is transparent to end users of logs
-  Log4j version is upgraded to 2.17.2
-  Create PR
-  Create Release notes

## Built With

* [Java](https://docs.oracle.com/javase/8/docs/api/)
* [Spring](https://docs.spring.io/spring-framework/docs/current/reference/html/)
* [Spring Initializr](https://start.spring.io/)

## Resources
- [start.spring](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.7.2&packaging=war&jvmVersion=17&groupId=com.example&artifactId=log4j2_snmpTrap&name=log4j2_snmpTrap&description=Log4j%20migration%20story%20project%20for%20Spring%20Boot.%20Story%3A%20Migrate%20Selfcare%20Service%20(SIF)%20to%202.17.2%20of%20log4j%202%20So%20that%20vulnerabilities%20can%20be%20mitigated.&packageName=com.example.log4j2_snmpTrap&dependencies=devtools,web,security,data-jpa,h2,postgresql)
- [Ryan's initial work!!!](https://dev.azure.com/Digicel-DevOps/AD_Applications/_git/service-selfcare/pullrequest/10234?_a=files&path=/config/log4j.xml)
- [log4j2-snmp-appender_GitHub_Template](https://github.com/DushmanthaBandaranayake/log4j2-snmp-appender)
- [log4j2-snmp-appender_Stackoverflow_redirect](https://stackoverflow.com/questions/54249551/how-to-configure-snmp-appender-in-log4j2-xml)
- [DailyRollingFileAppender](https://stackoverflow.com/questions/30882982/in-log4j-1-2-to-log4j-2-migration-what-to-do-with-the-dailyrollingfileappender)

## Acknowledgments

[@shaviyavictor](https://stackoverflow.com/users/17420216/shaviyavictor?tab=bookmarks)

### Author

* **Victor Shaviya**
    - [BioLink](https://bio.link/shaviya)
    - [LinkedIn](https://www.linkedin.com/in/ShaviyaVictor/)
    - [Instagram](https://www.instagram.com/shaviyavictor/)


**© Victor Shaviya**, Project Guide Template.