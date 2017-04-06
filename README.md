
Example P2 site generator
=========================

Requires Maven to run.

 * To build the update site : ```mvn clean package```. Result will be in ```$root/target/repository```
 * To host the site locally : ```mvn clean package jetty:run```. Update site will be available under ```http://localhost:8088/```

The categories can be edited with the ```catecory.xml``` file (referenced from ```pom/xml``` @ line 44).
