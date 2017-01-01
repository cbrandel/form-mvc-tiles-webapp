This is an example showing how to use Spring MVC's annotation-based configuration for a 
CRUD form using Hibernate.

This project can be built using Maven (http://maven.apache.org).  It can also be imported into 
the Eclipse IDE, but the M2Eclipse plugin should be installed since it is used to resolve 
the classpath.  The project is also setup to use the Spring IDE (http://springide.org).
	
It can also be run from the command line with 'mvn jetty:run' and accessed at the url 
'http://localhost:8080/form-mvc-tiles-webapp'.

Webapp based on 
https://github.com/spring-by-example/spring-by-example/tree/master/web/dynamic-tiles2-webapp
to use more standard and recent libraries 

Release Notes
--------------
2.0.0 - Forked from https://github.com/spring-by-example/spring-by-example
		Created standalone version
		Changed from HSQLDB to H2
		Upgraded to Spring 4.3
		Upgraded to Hibernate 5.2
		Remove sbe-dynamic-tiles2 dependency
		
1.1.4 - Upgraded to Spring 4.1.4.

1.1.3 - Upgraded to Spring 4.0.2.

1.1.2 - Upgraded to use Spring Data JPA.

1.1.1 - Upgraded to Spring 3.2.

1.1   - Upgraded to Spring 3.0 and changed Spring MVC configuration to use 
        the new Spring MVC namespace.

1.0.2 - Updated to use JPA.

1.0.1 - Updated to use convention based Spring MVC configuration.

1.0 -	Initial release.
