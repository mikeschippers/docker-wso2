Build, ship and run WSO2 Software using Docker 
=================== 

WSO2 Enterprise Service Bus
----------------------------------
Build:

    docker build -t="wso2esb:4.9.0" .

Run:

    docker run -ti -p 9443:9443 mikeschippers/wso2esb:4.9.0



WSO2 API Manager
----------------------------------
Build:

    docker build -t="wso2am:1.10.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 mikeschippers/wso2am:1.10.0
	

WSO2 Application Server
----------------------------------
Build:

    docker build -t="wso2as:5.3.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 mikeschippers/wso2as:5.3.0	


WSO2 Data Analytics Server
----------------------------------
Build:

    docker build -t="wso2das-3.0.1" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 mikeschippers/wso2das-3.0.1
	