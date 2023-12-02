## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- Service-oriented architecture (SOA) is an enterprise-wide approach to software development that takes 
advantage of reusable software components, or services. Each service is comprised of the code and data 
integrations required to execute a specific business function—for example, checking a customer’s credit, 
signing in to a website, or processing a mortgage application.

2. List and discuss the characteristics of SOA.
- Standardized Service Contracts: Services adhere to a service description.
- Loose Coupling: Services minimize dependencies on each other and create specific types of relationships within and outside of 
service boundaries with a constant emphasis on reducing dependencies between service contract, service implementation, and service consumers.
- Abstraction: Services hide the logic they encapsulate from the outside world. 
- Service Reusability: Logic is divided into services with the intent of maximizing reuse.
- Autonomy: Services should have control over the logic they encapsulate.
- Statelessness: Incorporate state management deferral extensions within a service design goal.
- Discoverability: Services can be discovered (usually in a service registry).
- Composability: Services break big problems into little problems. This is elated to the Reusability principle.
- Interoperability: Services should use standards that allow diverse subscribers to use the service.

3. Define Microservices.
- Microservices are a cloud-native architectural approach that simplifies code updates, allows for independent 
component scaling, and reduces waste and cost associated with entire applications due to excessive load on a single feature.

4. List and discuss the benefits of using Microservices.
- Independently deployable: Perhaps the single most important characteristic of microservices is that because the services are smaller and 
independently deployable Microservices promise organizations an antidote to the visceral frustrations associated with small changes taking huge amounts of time. 
- Right tool for the job 
Traditional n-tier architecture patterns involve an application sharing a common stack and large relational database, 
but this approach has drawbacks, as every component must share the same stack, data model, and database, 
even if there's a better tool for certain elements.
- Precise scaling
Microservices enable individual deployment and scaling of services, requiring less infrastructure than monolithic applications. 
They allow precise scaling of only required components, reducing the need for the entire application.

5. List and discuss the similarities and differences of SOA and Microservices.
DIFFERENCE
- Reuse
SOA focuses on reusability of integrations, increasing scalability and efficiency. 
Microservices architecture reduces agility and resilience by reducing dependencies 
and promoting code reuse through copying and data duplication.
- Synchronous calls
SOA reusable services use synchronous protocols, but real-time dependencies in microservice applications can reduce resilience and performance. 
Asynchronous communication patterns, like event sourcing, are preferred for microservices applications, allowing components to stay updated on data changes.
- Data duplication
SOA aims for synchronous data synchronization, reducing complexity. Microservices should have local access to data, 
ensuring independence from other microservices and applications, even if it involves duplication of data.

SIMILARITIES
- Both are collections that focus on performing specific functions.
- Both are smaller in overall scope than one large monolithic architecture.
- Both require decentralization in the internal culture with cross-functional collaborative abilities.
- Both allow the choice of program languages that best suit each service.

6. Define Web Services.
- It is any piece of software that makes itself available over the internet and uses a standardized messaging system.

7. List and discuss the benefits of using Web Services.
- Exposing the Existing Function on the network
A web service is a unit of managed code that can be remotely invoked using HTTP. That is, it can be activated using HTTP 
requests. Web services allow exposing the functionality of existing code over the network.
- Interoperability
It allows applications to talk to each other and share data and services among themselves. 
- Standardized Protocol
It is use in web services to standardized industry-standard protocol for 
communication. All four layers (Service Transport, XML Messaging, Service Description, and Service Discovery layers) 
use well-defined protocols in the web services protocol stack. This gives the business many advantages such as a wide range of choices, 
reduction in the cost due to competition, and increase in quality.

- Low Cost Communication
It uses SOAP over the HTTP protocol, so you can use your existing low-cost internet for implementing web services.

8. List and discuss the characteristics of Web Services.
- XML-Based
It uses XML at data representation and data transportation layers. 
XML eliminates any networking, operating system, or platform binding. 

- Loosely Coupled
A web service's consumer is not tied to that web service directly. The web service interface can change 
over time without compromising the client's ability to interact with the service.

- Coarse-Grained
Object-oriented technologies like Java expose services through individual methods, providing useful capabilities at a corporate level. 
These interfaces should be coarse-grained, allowing businesses to access the right amount of business logic. 
Web services technology provides a natural way to define these services.

- Ability to be Synchronous or Asynchronous
Synchronicity is the client's binding to a service's execution, allowing it to block and wait for the service to complete before continuing. 
Asynchronous operations allow clients to invoke a service and execute other functions, allowing them to retrieve results later, enabling loosely coupled systems.

- Supports Remote Procedure Calls (RPCs)
Web services enable clients to execute procedures, functions, and methods on remote objects via an XML-based protocol, 
exposing input and output parameters that the service must support.

- Supports Document Exchange
XML offers a versatile way to represent data and complex documents, from simple addresses to entire books or Request for Quotation (RFQ). 
Web services facilitate transparent document exchange, enhancing business integration.

9. List and discuss the distinct roles in Web Services Architecture.
- Provider
The provider creates the web service and makes it available to client applications who want to use it.
- Requestor 
A requestor is a client application that needs to contact a web service, such as .Net or Java, 
to access functionality through a web service.
- Broker
The broker is an application that grants access to the UDDI, which enables the client application to locate the web service.

10. List and discuss the Web Services Components.
- SOAP is an XML-based protocol for exchanging information between computers, running on any operating system. 
It encodes HTTP headers and XML files for communication between two computers. 
- WSDL is an XML-based language for describing web services and accessing them. 
It is an integral part of UDDI, facilitating businesses to be listed on the Internet.
- UDDI is an XML-based standard for describing, publishing, and finding web services. 
It stands for Universal Description, Discovery, and Integration, and is an open framework and platform-independent. 
It uses WSDL to describe interfaces to web services and is a specification for a distributed registry of web services.
