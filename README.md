This is the most basic sample web application for Spring Security.

I've migrated it from Gradle to Maven, because
[I could not compile it with Gradle](http://forum.springsource.org/showthread.php?120235-Trying-to-run-the-sample-code-of-Spring-Security-3-1),
and I didn't receive any response in the forum at the time of writing this.

Additional useful links:

* [Spring Security Tutorial description and other resources](http://static.springsource.org/spring-security/site/start-here.html)
* [Spring security full source code, including this sample application](http://static.springsource.org/spring-security/site/source.html) (without my modifications)
* [GitHub page containing this source code](https://github.com/stivlo/security-tutorial)

Easy way to start the test application:

    $ mvn jetty:run 

or 

    $ mvn tomcat:run

The 'scripts' directory contains simple Unix command-line scripts for exercising the application and displaying the results.


