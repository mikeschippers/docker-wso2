Build, ship and run WSO2 Software using Docker 
=================== 

WSO2 Enterprise Service Bus
----------------------------------
Build:

    docker build -t="wso2esb:4.9.0" .

Run:

    docker run -ti -p 9443:9443 wso2esb:4.9.0



WSO2 API Manager
----------------------------------
Build:

    docker build -t="wso2am:1.10.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 wso2am:1.10.0

