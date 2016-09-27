glassfish
======================
Quick environment for developing Web applications.

Author: Ming Zhao mingyu.zhao@gmail.com

Requirements
------------
Docker

Configuration
---------------
In “config.json”, you can set the port and endpoints of API services, as well as WSO2 IS params.

Installation
------------
docker build -t my-glassfish . 

docker run -it --rm --name my-running-glassfish -p 8080:8080 -p 4848:4848 -p 8181:8181 my-glassfish


Testing
-----------
Given:

Container IP: 192.168.99.100 

Then go to:

http://192.168.99.100:8080


Resources
---------
* [Docker](http://www.docker.com)



