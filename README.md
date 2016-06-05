Build, ship and run WSO2 Software using Docker 
=================== 

WSO2 API Manager
----------------------------------
> WSO2 API Manager is a complete solution for designing and publishing APIs, creating and managing a developer community, and for scalably routing API traffic. It leverages proven, production-ready integration, security, and governance components from the WSO2 Enterprise Service Bus, WSO2 Identity Server, and WSO2 Governance Registry. In addition, it leverages the WSO2 Data Analytics Server for analytics, giving you instant insight into APIs behavior. [More info.](http://wso2.com/api-management/)

Build:

    docker build -t="mikeschippers/wso2am:1.10.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2am:1.10.0


WSO2 App Manager
----------------------------------
> WSO2 App Manager is a complete solution for publishing and managing all aspects of an application and its lifecycle. 100% open source, it also provides an unique one-stop store solution where users can pick and choose apps, and is highly scalable. [More info.](http://wso2.com/products/app-manager/)

Build:

    docker build -t="mikeschippers/wso2appm:1.1.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2appm:1.1.0


WSO2 Application Server
----------------------------------
> Your Web application is valuable to your users‚ and increasingly valuable to mobile applications, integration consumers, business processes, workflows, and analytics. With the WSO2 Application Server, you can easily share business logic, data, and process across the entire IT ecosystem. The WSO2 Application Server is cloud native, providing a firm foundation for hosting shared, multi-tenant, elastically scaling SaaS applications. [More info.](http://wso2.com/products/application-server/)

Build:

    docker build -t="mikeschippers/wso2as:5.3.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2as:5.3.0

WSO2 Business Process Server
----------------------------------
> The 100% open source, highly scalable and lean WSO2 Business Process Server helps to increase productivity and enhance competitiveness by enabling developers to easily deploy business processes and business models written using WS-BPEL and BPMN standards respectively. It also serves as the business process management and hosting environment for your SOA. [More info.](http://wso2.com/products/business-process-server/)

Build:

    docker build -t="mikeschippers/wso2bps:3.5.1" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2bps:3.5.1

WSO2 Business Rules Server
----------------------------------
> The WSO2 Business Rules Server brings the agility of business rules to your SOA toolkit. Based on a solid platform for hosting business rules, our Business Rules Server excels at extending the capabilities of your SOA. [More info.](http://wso2.com/products/business-rules-server/)

Build:

    docker build -t="mikeschippers/wso2brs:2.2.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2brs:2.2.0 
    
WSO2 Complex Event Processor
----------------------------------
> WSO2 Complex Event Processor (WSO2 CEP) helps identify the most meaningful events and patterns from multiple data sources, analyze their impacts, and act on them in real time. 100% open source, it allows you a set up a more agile connected business, responding to urgent business situations with both speed and precision. [More info.](http://wso2.com/products/complex-event-processor/)

Build:

    docker build -t="mikeschippers/wso2cep:4.1.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2cep:4.1.0

WSO2 Dashboard Server
----------------------------------
> The WSO2 Dashboard Server helps to rapidly create visually appealing and engaging web components such as dashboards, and gadgets, and unlocking data for business intelligence and monitoring. With the host of capabilities that Dashboard Server provides out-of-the-box, going from data to screen has never been easier. [More info.](http://wso2.com/products/dashboard-server/)

Build:

    docker build -t="mikeschippers/wso2ds:2.0.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2ds:2.0.0

WSO2 Data Analytics Server
----------------------------------
> WSO2 Data Analytics Server is a comprehensive enterprise data analytics platform; it fuses batch and real-time analytics of any source of data with predictive analytics via machine learning. It supports the demands of not just business, but Internet of Things solutions, mobile and Web apps. [More info.](http://wso2.com/products/data-analytics-server/)

Build:

    docker build -t="mikeschippers/wso2das:3.0.1" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2das:3.0.1

WSO2 Data Services Server
----------------------------------
> WSO2 Data Services Server augments service-oriented architecture development efforts by providing an easy-to-use platform for integrating data stores, creating composite data views, and hosting data services. It supports secure and managed data access across federated data stores, data service transactions, and data transformation and validation using a lightweight, developer friendly, agile development approach. [More info.](http://wso2.com/products/data-services-server/)

Build:

    docker build -t="mikeschippers/wso2dss:3.5.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2dss:3.5.0

WSO2 Enterprise Service Bus
----------------------------------
> WSO2 Enterprise Service Bus is a lightweight, high performance, and comprehensive ESB. 100% open source, the WSO2 ESB effectively addresses integration standards and supports all integration patterns, enabling interoperability among various heterogeneous systems and business applications. [More info.](http://wso2.com/products/enterprise-service-bus/)

Build:

    docker build -t="mikeschippers/wso2esb:4.9.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2esb:4.9.0


WSO2 Enterprise Store
----------------------------------
> Organizations generate large volumes of assets. Business units distributed geographically and functionally often duplicate overlapping assets. These overlaps cause wastages in capital and time for enterprises. For this reason, the enterprise store is finding its place at the centre of a connected business as an efficient tool to discover, manage lifecycle states and monetize enterprise assets. [More info.](http://wso2.com/products/enterprise-store/)

Build:

    docker build -t="mikeschippers/wso2es:2.0.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2es:2.0.0


WSO2 Machine Learner
----------------------------------
> WSO2 Machine Learner takes data one step further, pairing data gathering and analytics with predictive intelligence: this helps you understand not just the present, but to predict scenarios and generate solutions for the future. [More info.](http://wso2.com/products/machine-learner/)

Build:

    docker build -t="mikeschippers/wso2ml:1.1.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2ml:1.1.0

WSO2 Message Broker
----------------------------------
> The 100% open source WSO2 Message Broker is a lightweight, easy-to-use, distributed message-brokering server. It features high availability (HA) support with a complete hot-to-hot continuous availability mode, the ability to scale up to several servers in a cluster, and no single point of failure. It is designed to manage persistent messaging and large numbers of queues, subscribers and messages. [More info.](http://wso2.com/products/message-broker/)

Build:

    docker build -t="mikeschippers/wso2mb:3.1.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2mb:3.1.0 

	
WSO2 Identity Server
----------------------------------
> As the industry’s first enterprise identity bus (EIB), WSO2 Identity Server is the central backbone that connects and manages multiple identities across applications, APIs, the cloud, mobile, and Internet of Things devices, regardless of the standards on which they are based. The multi-tenant WSO2 Identity Server can be deployed directly on servers or in the cloud, and has the ability to propagate identities across geographical and enterprise borders in a connected business environment. [More info.](http://wso2.com/products/identity-server/)

Build:

    docker build -t="mikeschippers/wso2is:5.1.0" .

Run:

    docker run -ti -p 9443:9443 -p 9763:9763 -p 8280:8280 mikeschippers/wso2is:5.1.0 	