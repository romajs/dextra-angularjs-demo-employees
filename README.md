angularjs-dx-demo-employees
===========================

AngularJS Sample.

A small CRUD application for employees management.

This is a demo project featuring AngularJS, RestEasy, CDI and JPA/Hibernate running with Jetty and HsqlDB.

![](http://s6.postimg.org/vg3qep3ox/demo_angularjs_employees.png)

Requirements:

* Java JDK 7+: http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html
* Apache Maven 3+: https://maven.apache.org/download.cgi


Build with maven:

	mvn clean install

Run with maven jetty plugin:

	mvn jetty:run

Application URL access:

	http://localhost:8080/employees/

Database reset:

	http://localhost:8080/employees/reset

Run functional tests with Angular Scenario Test Runner:

	http://localhost:8080/employees/test/runner.html
	
![](http://s6.postimg.org/4jjr6dkvl/demo_angularjs_employees_tests.png)
