**LICENSE**

Servers are licensed under their respective projects ONLY.

They are included here for development purposes ONLY. Please see respective project sites for more details.

**Servers and Versions**
* [Blazegraph Build Version 2.1.0](https://www.blazegraph.com/)
* [Fedora (fcrepo4) Release 4.5.1](https://github.com/fcrepo4/fcrepo4)
* [Apache Karaf Container Version 4.0.5](http://karaf.apache.org/)

**Requirements**
* Java 8 JDK
* Java ENV set
* Apache Maven
* Screen to use `launch_servers.sh` (optional)

**Running Each Server**

Note that I run these commands individually to monitor the server console and output.
* `java -server -jar blazegraph.jar`
* `java -jar fcrepo-webapp-4.5.1-jetty-console.jar`
* `./apache-karaf-4.0.5/bin/karaf server


OR `cd.. && ./launch_servers.sh``

@WORK IN PROGRESS
