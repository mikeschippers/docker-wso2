FROM debian:jessie

MAINTAINER Mike Schippers <info@mikeschippers.com>

RUN apt-get update && apt-get install wget unzip openjdk-7-jre curl -y && \ 
	groupadd -r wso2 -g 433 && \
	useradd -u 431 -r -m -g wso2 -d /home/wso2 -s /bin/bash -c "WSO2 Docker user" wso2 && \
	chown -R wso2:wso2 /home/wso2 && \
	mkdir /opt/wso2 && \
	wget -U firefox -P /tmp http://product-dist.wso2.com/products/enterprise-store/2.0.0/wso2es-2.0.0.zip && \
	unzip /tmp/wso2es-2.0.0.zip -d /opt/wso2/ && \
	rm -f /tmp/wso2es-2.0.0.zip && \
	sed -i 's/<!--MgtHostName>.*<\/MgtHostName-->/<MgtHostName>0.0.0.0<\/MgtHostName>/g' /opt/wso2/wso2es-2.0.0/repository/conf/carbon.xml && \
	chown -R wso2:wso2 /opt/wso2

ENV JAVA_HOME /usr/lib/jvm/java-7-openjdk-amd64/	
	
USER wso2
	
EXPOSE 9443 9763 8243 8280 10397 7711

ENTRYPOINT ["/opt/wso2/wso2es-2.0.0/bin/wso2server.sh"]