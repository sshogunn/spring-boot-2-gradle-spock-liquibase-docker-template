# Project generator from template
 Allows to generate a project with Spring Boot 2 M7, Gradle 4.3, Spock 1.1, Liquibase 3.5.3, Open Table for PostgreSQL, Spring Data 
 
# How to generate a project
Use the following command: 
*gradle cleanArch generate -i -Dtarget=generated -Dgroup=com.xxx.yyy -Dname=dummy-service -Dversion=1.0-SNAPSHOT* 
in the project root. You can find generated project in *generated* folder
