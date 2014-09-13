#  Welcome to **[jQuaternion](http://stryng.github.io/JQuaternion)**
_An out-of-the-box Java APP MVC framework on s73r01ds_
##### Current Build Status 
![jQuaternion](https://travis-ci.org/stryng/JQuaternion.svg) @ [Travis](https://travis-ci.org/stryng/JQuaternion)
##  Tech stack
###  Client side

* Massive Responsive Web Design
* [HTML5 Boilerplate](http://html5boilerplate.com/)
* [Twitter Bootstrap](http://getbootstrap.com/)
* [AngularJS](https://angularjs.org/)
* Full internationalization support with [Angular Translate - i18n](http://angular-translate.github.io/)
* Optional Compass / Sass support for CSS design
* Optional WebSocket support with the [Atmosphere Framework](http://async-io.org/release.html)
* Easy installation of new JavaScript libraries with [Bower](http://bower.io/)
* Build, optimization and live reload with [Grunt](http://gruntjs.com/) or [Gulp.js](http://gulpjs.com/)
* Testing with [Karma](http://karma-runner.github.io/) and [PhantomJS](http://phantomjs.org/)
* Support for the [Thymeleaf](http://www.thymeleaf.org/) _(sorry JSP, JSTL l0v3rs)_ template engine

### Tech stack on the server side
* [Spring MVC](http://projects.spring.io/spring-framework/) Java Application Delivered
* The great jhipster Loaded agent which extends Spring Loaded to give you hot reload of your Java code, Spring * * Beans, and many more...
* [Spring Boot](http://projects.spring.io/spring-boot/) for easy application configuration
* [Maven](http://maven.apache.org/) or [Gradle](http://www.gradle.org/) configuration for building, testing and running the application
* "_Development_" and "_Production_" profiles (both for [Maven](http://maven.apache.org/) and [Gradle](http://www.gradle.org/))
* [Spring Security](http://projects.spring.io/spring-security/)
* [Spring DATA REST](http://projects.spring.io/spring-data-rest/) + [Jackson](http://jackson.codehaus.org/)
* Optional WebSocket support with the [Atmosphere Framework](http://async-io.org/release.html)
* [Spring Data JPA](http://projects.spring.io/spring-data-jpa/) + Bean Validation
* [Hibernate](http://hibernate.org/) [H2](http://www.h2database.com/), [HyperSQL](http://hsqldb.org/), [MySQL](http://www.mysql.com/) and [Oracle](http://www.oracle.com/us/products/database/overview/index.html) Dialects Integration on the fly
* Database updates with [Liquibase](http://www.liquibase.org/)
* [MongoDB](http://www.mongodb.com/) support if you'd rather use NoSQL instead of a classical relational database
* Ready to go into from UAT -> Production switch hot release branching cross all the above
* Monitoring with Metrics ([PSI-Probe](https://code.google.com/p/psi-probe/) based approach, thanks to Ralf Krauß)
* Caching with [ehCache](http://ehcache.org/)(local cache) or [hazelcast](http://hazelcast.com/)(distributed cache)
* Optional HTTP session clustering with [hazelcast](http://hazelcast.com/)
* Optimized static resources (gzip filter, HTTP cache headers)
* Log management with Logback, configurable at runtime
* Connection pooling with [HikariCP](http://brettwooldridge.github.io/HikariCP/) for optimum performance
* Builds a standard WAR file or an executable JAR file
* Integration with [Apache Tomcat](http://tomcat.apache.org/), [Weblogic](http://www.oracle.com/technetwork/middleware/weblogic/overview/index.html), [Websphere](http://www-01.ibm.com/software/websphere/) and [JBoss](http://www.redhat.com/en/technologies/jboss-middleware)