## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- Service-Oriented Architecture (SOA) is a technique, method, or approach used in an enterprise to fully utilize software components called services. This is done by combining services in such a way that they can function as one to create and perform a defined business process, function, or application. These services can communicate with each other even across different platforms and systems using standard communication protocols, which ensures their reusability.

2. List and discuss the characteristics of SOA.
- Standardized Service Contracts: It has a standardized service contract that requires proper adherence. This results in service contracts being expressed more formally since they follow a certain standard.
- Loose Coupling: Services in SOA are independent of each other, or at least are made to be less dependent on each other. It reduces the risk of services being too associated with each other that when changes are applied in a service, the associated service(s) are noticeably affected, be it in terms of performance or other affection that could result negatively between the relationships of services.
- Abstraction: It hides the details of a service and the logic behind it, making it inaccessible from the outside world. Making the use of services more secure, confidential, and safe to use within the organization only.
- Service Reusability: Each service has a different logic in it; it is divided into specific and unique logics, making them easy to reuse and combine with other services, which ensures efficiency and consistency.
- Autonomy: Services have authority over their own logic, giving them the ability to perform their logic despite influences from other services. For it to work, services must have more isolation and be more reliable and predictable.
- Statelessness: Stateless services are more ideal because they save on the consumption of resources by separating the services from their state, making them able to handle processes more reliably.
- Discoverability: Services are usually stored in a service registry, making them easier to find or discover. Service contracts contain accurate metadata for discovery, which also contains purposes and capabilities comprehensible to humans.
- Composability: Services are composable in that they can be combined and assembled in various ways to create a specific business process. It is made to be worked with in many ways to ensure flexibility.
- Interoperability: Services are operable across different platforms and systems because they communicate using standard communication protocols. Making it possible for them to work together easily.

3. Define Microservices.
- Microservices architectures are like SOAs; they contain services, but they are also called microservices that are also loosely coupled, reusable, and specialized components. Microservices are mainly made to create individual applications composed of independently deployable smaller components or services (microservices). Furthermore, microservices are cloud-native, making them more accessible to the team.

4. List and discuss the benefits of using Microservices.
- Independently Deployable: Each application created using microservices is composed of smaller pieces of components that can easily be utilized to fix something in the application, create small changes in a short amount of time, and more. This could be possible because an organization can assign teams to each service or set of services that are cross-functional and operable in an agile fashion.
- Right Tool for the Job: Applications composed of smaller parts or services are always easier and more desirable to update, upgrade, or modify than a single large application. It is also cost-efficient since it is easier to maintain.
- Precise Scaling: Its scale is controllable because services can be deployed individually. The organization has control over which services they are going to deploy for an individual application.

5. List and discuss the similarities and differences of SOA and Microservices.
Similarities:
- Both contain loosely coupled, reusable, and specialized components.
- Both are architectural methods that help with the optimization and utilization of applications.
- Reusability, scalability, flexibility, and agility are common principles in these architectures.
- Both aim to reduce dependence between services.
Differences:
- The main difference is that SOA is used enterprise-wide, while microservices are application-specific. This makes SOA appear to be larger and more complex than microservices.
- Deployment in SOA may not be as independent as in microservices. SOA mostly deploys sets of components or services, while microservices are designed to deploy components independently.
- SOA tends to be more impactful because of its enterprise-wide scope than microservices.
- Communication: Microservices has its own communication protocol for its services, while SOA requires each service to share a common communication system (ESB).
- Interoperability: SOAs focus more on heterogeneous or standardized messaging protocols, while microservices often make things simpler by using lightweight messaging protocols.
- Service Granularity: SOA services can range from small to enterprise-wide services or components, while microservices mainly focus on small but highly specialized services designed to have a singular function.
- Speed: While SOAs development is more simplified, microservices architectures favor duplication rather than mainly sharing, which makes microservices architectures operate faster.

6. Define Web Services.
- Web services are any services that are accessible via the internet. Web services tends to be more of a simpler process which makes it different from web applications and by web services being a simpler and smaller processes, there are often used as an integrated process for web applications, software, and more. Examples of web services include; registration of accounts using a Facebook account or a Google account, making payments online, google web services (GWS), etc. Its process is simple but effective, servers are used to host or store the web services then it is accessible by the client or user using the internet. The client requests, the internet acts as a middleman and sends the request to the server, then the server responds back using the internet as well.

7. List and discuss the benefits of using Web Services.
- Exposing the existing function on the network: With the use of web services, functionalities of codes are easily exposed over the network by activating it remotely using HTTP/HTTP request. This makes it available for other applications to be used through integration and implementation.
- Interoperability: Web services makes it possible for different applications to communicate with each other which allows them to exchange data and services.
- Standardized protocol: Web services follows an industry-standard set of protocol for communication. Quality assurance, cost reduction, and wide range of options are benefits of web services because it uses a standardized protocol.
- Low Cost Communication: Web services use SOAP (Simple Object Access Protocol) over HTTP protocol. SOAP uses wide range of communication protocols making it possible for web services to be implemented using cheap internet.

8. List and discuss the characteristics of Web Services.
- XML-Based: XML is used by the web services for data representation and data transportation layers. This enables web services to be highly interoperable at their core level.
- Loosely Coupled: The client or consumer of a web service does not make them be dependent directly to the web service. Meaning, the client and server logic are not dependent on each other and that allows interface changes without updating the any other interface/s.
- Coarse-grained: Web services makes services be represented in a simpler way while also providing only the right amount of business logic.
- Ability to be synchronous or asynchronous: Web services allow the client to operate synchronously or asynchronously. This makes them get their results right after the process (synchronous) or later (asynchronous).
- Support remote procedure calls: Since web services are XML-based, it allows the client to invoke on remote objects.
- Supports document exchange: Web services allow simple and complex documents to be exchangeable and be used in better facilitation of business integration.

9. List and discuss the distinct roles in Web Services Architecture.
- Provider: These are the creator/s of web services and are also responsible for making it available to be used to client applications.
- Requestor: These are the client application/s in which web services are used or implemented to achieve additional functionalities.
- Broker: These are the provider of access to UDDI which gives the client application ability to locate a web service.

10. List and discuss the Web Services Components.
- SOAP (Simple Object Access Protocol): Web services uses SOAP as its communication protocol. SOAP is cross-platform which makes it to operate independently on any platform and languages. It provides an encoding description and it allow service firewalls. Additionally, SOAP is the reason why web services is able to provide low cost communication.
- WSDL (Web Services Description Language: WSDL is a XML-based language that provides description of web services and how to access them. It is an important part of UDDI that makes it possible for business to be listed and the services that they are providing.
- UDDI (Universal Description, Discovery and Integration: UDDI is also platform-independent and it is responsible for providing description, publication, and visibility of web services. As mentioned, WSDL is an integral part of UDDI as it uses it to describe interfaces to web services.
