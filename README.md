To build the application:

From the command line with Maven installed:

$ cd spring-boot-pagination 
$ mvn clean install
Run the application from Tomcat

Increase heap space to 1024 m or at least 512 m

Heap space configuration in Tomcat:

If you are using Tomcat, edit catalina.bat for windows users or catalina.sh for linux / Mac users

in Windows
set JAVA_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=256m" 

in Linux / Mac
export JAVA_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=256m" 
Run the application from Spring boot

   $ cd spring-boot-pagination
   $ mvn spring-boot:run
Run the application from Spring boot in eclipse

<b>Pagination URL </b> <br/>
http://localhost:8080/listPageable?page=0&size=3&sort=name

