## Long Quiz in Advanced Systems Integration & Architecture
1.	Define Service Oriented Architecture (SOA).
-	SOA or Service Oriented Architecture is a software development that allows reusability of services. SOA are applied to other application that need services from other application that has existing services that they can use, and in that matter, those said services will communicate with each other in order to work together. There is a technique that is used for eliminating the dependencies between the components in a system or network so that they can exchange data or manage business activity, and this technique or method is called loose coupling.
2.	List and discuss the characteristics of SOA.
-	It supports loose coupling – Just like on what I have mentioned above, this eliminates the dependencies between the components and for this reason, if the service functionality fails, it should not have a disastrous effect on the client application or cause it to crash.
-	It supports interoperability – in here, it follows a certain criterion that enable various customer or client to utilize the service.
-	Standardized Service Contracts – It contains some information that explains its purpose for the client’s safety. 
-	Abstraction - The way the service operates should not be visible to anyone for the safety of both client and customer or the company. 
-	Service Reusability – The logic here is divided so that it will be easy to re-use the service if there is a specific logic or services that they want to use.
-	Autonomy – Just like the abstraction, the logic here must be encapsulated and they must control which logic should be encapsulated so that the services will be more isolated.
-	Statelessness – In here from what I understand, the data should be stateless in order to increase the service scalability.
-	Discoverability – Another characteristic of SOA is that it is discoverable, in a way that they provide relevant information for easy identification and by including details about their purpose and capabilities so that people can easily understand it.
-	Composability – Here in composability, just like dividing the logic, big problems are divided into smaller and more manageable problem which is in lined for the Reusability principle.
3.	Define Microservices.
-	Based on what I understand, Microservices is made up of loosely coupled, reusable and specialized components which can be broken into smaller pieces for easy configuring or such. Unlike SOA that has an enterprise focus, microservices are built for individual applications which makes it more agile or flexible as well as scalable.
4.	List and discuss the benefits of using Microservices.
-	Independently deployable – One of the benefits of Microservices is that they are remedy for those problems that takes too much time in solving even if it is minor changes because of Microservices being smaller and its nature of being independent deployable.
-	Right tool for the job – Another is that it gives you a freedom to choose the most effective tool that you see fit for a specific task as well as gives you flexibility to choose tools that is suitable for solving unique challenges that you may encounter.
-	Precise Scaling – This is also a benefit of Microservices because from what I have understand, since the Microservices are deployed and scaled independently, if there is a problem that occurs in the future it would be easy to spot it and you can configure only the specific part or component you needed or has problem.
5.	List and discuss the similarities and differences of SOA and Microservices.
-	Differences:
-	Scope - SOA and Microservices differ in scope because SOA have an enterprise focus, it is loosely coupled that is why it is easy for others to re-use the functionality of other applications. While, Microservices, with an application focus, just like what I have mentioned above, it operates independently and it can be broken into smaller pieces and can be scaled or administered independently.
-	Communication - Microservices has its own way of talking to others because as it is developed independently then it has its own communication protocol that is used. While, SOA relies on a common Enterprise Service Bus (ESB) and that each service must have this ESB, that puts it at risk because if it fails, it affects everything or if one single service slows down then it will also slow down other services. 
-	Interoperability - Microservices sets simplicity in message sending, whereas SOA is open for more complex or complicated way. 
-	Service Granularity - Microservices is designed in doing a specialized task or one specific task, while SOA include both specialists and those who can handle tasks for the whole company. 
-	Speed - Microservices prefer duplication because it contributes to faster operation, while SOA uses common architecture resulting for its slowing down development and problem-solving.
-	Similarities:
-	SOA and Microservices similar in terms of they both break down big applications into smaller and flexible parts that works together but with different purposes. 
6.	Define Web Services.
-	Web Services based on my understanding is that it is any software that is made available with the use of internet and it also uses standardized messaging system. 
7.	List and discuss the benefits of using Web Services.
-	Exposing the Existing Function on the network – Just like what the title means, Web Services can be remotely be invoked using the HTTP or Hypertext Transfer Protocol and so it can be activated using HTTP requests. So based on its title, once the web service is exposed on the network then all of its existing function will also be exposed and other applications can use the functionality of the program.
-	Interoperability – In interoperability, as web services is made available with the use of internet then it allows various application to communicate and share their services, data or resources among themselves. It made communication and sharing with others more easily.
-	Standardized Protocol – in terms of Standardized Protocol, it is mentioned here that there are four layers namely: Service Transport, XML Messaging, Service Description, and Service Discovery. In Web Services, they offer standardized protocol so that they can give the businesses a wide range of choices, cutting off some cost due to competition as well as to increase the quality. 
-	Low-Cost Communication – Web Services also offers low-cost communication as you can use your existing low-cost internet to deliver or implementing your web services. 
8.	List and discuss the characteristics of Web Services.
-	XML-Based – Web Services are XML based for the reason that it eliminates any networking, operating system or platform binding. It is also because XML is used for data representation and data transportation layers.
-	Loosely Coupled – One of the characteristics of Web Services is it is loosely coupled which means that the consumer is not directly tied to the web service. It is for the reason that Web Service interface is ought to change in some time and because it is loosely coupled it would not compromise the interaction of the consumer to the service. 
-	Coarse-Grained – the Coarse-Grained is about providing a natural way of accessing the right amount of business logic. 
-	Ability to be Synchronous and Asynchronous – Web Services has the ability to be synchronous in which it blocks and wait for the operation of the service to be completed before continuing. And asynchronous, it allows a client to invoke the service and execute other functions. 
-	Supports Remote Procedure Calls (RPCs) – using XML-based protocol Web Services supports clients to invoke procedures, functions and methods remotely. 
-	Supports Document Exchange – Web Services supports document exchange transparently in order to facilitate business integration. The documents said can be about representing current address or complex documents such as an entire book.
9.	List and discuss the distinct roles in Web Services Architecture.
-	Provider – the provider is the one who creates the web service and make sure that it is available to client application especially for those who wants to use it. 
-	Requestor – the role of requestor here is to be a bridge between the client application and web service, the client application can be any language-based application that looks for some functionality via web service. 
-	Broker – the broker acts as a finder in which it helps the client application to locate the web service and provide access to the UDDI, which will be discussed later on.
10.	List and discuss the Web Services Components. 
-	SOAP – from what I have understand SOAP which stands for Simple Object Access Protocol, it allows communication between applications or computers. It can also run on any operating system and can also allow server firewalls.
-	WSDL – WSDL or Web Services Description Language is the one who describe web services and how to access them. It involves process on how to access them as well as helps individuals to navigate businesses to access the service.
-	UDDI – UDDI is like the combination of the two and the standard of those two-web services component that is discussed above. UDDI stands for Universal Description, Discovery and Integration and it is an open framework and platform-independent which serves as the foundation of SOAP and WSDL.
