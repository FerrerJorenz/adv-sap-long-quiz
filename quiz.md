## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).

Service-Oriented Architecture (SOA): SOA is an approach to creating software applications that take advantage of reusable software components, and these components or services are made with code and data integrations in order to execute a function or action in a business.

2. List and discuss the characteristics of SOA.

Characteristics of SOA:

Standardized Service Contracts: Service providers follow the service description that they gave, in order for their service to be purposeful and be within their own range of capabilities.

Loose Coupling: This aims to make services for reliable when independent, but when needed can still function with other services to achieve the needed functionality.

Abstraction: The service or softwares are abstracted, because the consumers don't need to know the logic or workings of a service. It allows the service providers to change implementations but still maintain service to the consumers.

Reusability: Encourages the usage of existing services before creating new ones, promoting the reuse of services.

Autonomy: Services are able to function independently without the need of external influences or actions.

Statelessness: Services do not retain information about the previous interactions with clients. Minimizes resource consumption by shortening information while maintaining completeness.

Discoverability: Uses metadata for discovery, services are able to show their purpose and capabilities.

Composability: Breaks down complex problems into manageable parts to maximize efficiency.

Interoperability: Sets standards for services, ensuring subscribers can use them, it also ensures that different services or components can work together effectively even if they are developed by different service providers.

3. Define Microservices.

Microservices Definition:

Microservices, similar to SOA, is employed to build individual applications in a way that enhances scalability and resilience. It consists of small, independent components that, when combined, create larger applications, assembling services and treating it as a whole. Microservices are a way of building software where we use small, independent components that work together. 

4. List and discuss the benefits of using Microservices.

Benefits of Microservices:

Independently Deployable: Microservices allow for independent deployment, Smaller services makes it easier for teams to understand its code and they are able to offer various options for problem-solving.

Right Tool for the Job: Microservices provide flexibility by enabling each service to use its own language and framework, making communication with the chosen application easier.

Precise Scaling: Individual services can be precisely deployed, efficiently handling a large number of tasks simultaneously.

5. List and discuss the similarities and differences of SOA and Microservices.

Reuse: Both emphasize looking for existing services before creating new ones, but microservices lean towards code reuse through copying and accepting data duplication.

Synchronous Calls: Both involve synchronous calls, but microservices' synchronous calls may create real-time dependencies.
Differences:

Communication: SOA relies on an ESB (Enterprise Service Bus) and can become a single point of failure, while microservices use independent communication protocols and simpler messaging systems like APIs.

Interoperability: SOA sets standards for services, whereas microservices enable the exchange and use of information across systems.

Service Granularity: Microservices have highly specialized services designed for specific tasks, while SOA services can range from small and specialized to enterprise-wide services.

Speed: SOA simplifies development and troubleshooting but may operate more slowly than microservices. Microservices allow for quick deployment and testing of independent application pieces without affecting the entire application.

6. Define Web Services.

Web Services are softwares that are available to consumers through the internet.

7. List and discuss the benefits of using Web Services.

Exposing the Existing Function on the network: Web services expose the functionality of an existing code or system that a developer made over the network. Once it is on the network other apps can also implement or use the functionality of your program.

Interoperability: Web services allow different applications to communicate to each other by sharing data and services among themselves. 

Standardized Protocol: Web services use standardized industry-standard protocols for communication, this gives business enterprises many advantages such as reduction in cost to function and increased service quality.

Low Cost Communication: Web services can be implemented with just the internet which is very low cost compared to other options.

8. List and discuss the characteristics of Web Services.

XML-Based: Web services use XML which eliminate networking,operating system, and platform binding; making them highly interoperable.

Loosely Coupled: A consumer isn't restricted to a single web service, interfaces can change without compromising the ability to interact with the service.

Coarse-Grained: A single method should implement broader business logic that is useful for businesses at corporate level.

Ability to be Synchronous or Asynchronous: Web services can be synchronouse where client blocks and waits for the service to complete its operation before proceeding. It can also be asynchronous, where a client invokes a service then also execute other functions.

Supports Remote Procedure Calls: Clients can invoke procedures, functions, and methods on an object using XML-based protocol web services.

Supports Document Exchange: Through XML, web services can also represent complex documents, and it supports exchange of documents to integrate businesses.

9. List and discuss the distinct roles in Web Services Architecture.

Provider: These are the people who creates the web service and makes it available to others who want to access their service.

Requestor: These are client applications that contacts a web service.

Broker: A broker is an application that provides access to UDDI which allows the client application to locate the web service.

10. List and discuss the Web Services Components.

SOAP: An XML-based protocol for exchanging information between devices, it stands for Simple Object Access Protocol

WSDL: An XML-based language that describes web services and how to access them, it stands for Web Services Description Language.

UDDI: An XML-based standard for describing, publishing, and locating web services, it stands for Universal Description Discovery and Integration.
