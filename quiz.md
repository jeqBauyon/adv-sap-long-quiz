## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

-Service-oriented architecture (SOA) is a method in software development that uses components of software called services to create business applications.

2. List and discuss the characteristics of SOA.

Standardized Service Contracts - Services use contracts to describe what they do. The information is stored in a registry or profiles for them to find easy and understand.
Composability - Dividing tasks into smaller parts, It has flexible pieces that fit together to work.
Interoperability - It make sure that different services can work together with common rules, allowing easy access and use.
Loose Coupling –  Services have clear limits and connections to be more independent and not rely on each other.
Abstraction - It's about hiding the complicated details of how a service works, showing only what's important for others to connect. 
Service Reusability - Taking a big system and dividing it into smaller parts that can be used in different ways.
Autonomy - Service can do things on its own without depending on others. It makes the service more reliable and predictable by seeing how it works.
Statelessness - It helps them grow and work better. It makes their rules more flexible and easier to use reusable parts.
Discoverability - It can easily find services in a registry. It can also communicate well and have individual or group management.


3. Define Microservices.

-Microservices are computer programs that are created by using little building blocks rather than one large piece and each block has its own function and communicates with the others.

4. List and discuss the benefits of using Microservices.

-Executives and project leaders like microservices because they align with how they want to organize teams and projects, matching the way operations are managed.

5. List and discuss the similarities and differences of SOA and Microservices.

-In SOA, different parts of a building are shared and used by the entire company, like everyone in a big office building using the same meeting room. But with microservices, it's more like having individual house only. Each house has its own thing without relying too much on the others. So, SOA is like a big shared space for everyone in a company, while microservices are like separate houses that work on their own.

6. Define Web Services.

-It has rules for sending messages and can be accessed from a company's website to be used by other online tools or programs.

7. List and discuss the benefits of using Web Services.

Exposing the Existing Function on the network - It can help your program share what it can do with other programs on the internet. 
Interoperability -  Different systems can talk to each other and can share information in a way they both understand.
Standardized Protocol - It's a shared rules for talking to each other. If there is an options it can lower costs because of competition, and better quality for businesses.
Low Cost Communication - Web services use cost-effective SOAP over HTTP, unlike pricier options like EDI/B2B. They can also run on reliable transport methods like FTP.

8. List and discuss the characteristics of Web Services.

XML-Based - It is to share data, making sure they work well on different networks and devices.
Loosely Coupled - It can update things without messing up how you use it. But if it is connected closely, changes on one side mean changes on the other.
Coarse-Grained - It create tools that do the job well without being too specific.
Ability to be Synchronous or Asynchronous - Your client sticks with the service until it's done. The client waits for the service to finish before moving on.


9. List and discuss the distinct roles in Web Services Architecture.

Provider - The creator offers the web service for clients to use.
Requestor - A requestor is like an app that asks a web service to request something for a program.
Broker - The broker is the app that gives access to UDDI. UDDI helps the client app find the web service.

10. List and discuss the Web Services Components.

SOAP - Universal computer talk using XML that works with any system or language, and is friendly with firewalls.
WSDL -  Describes web services and how to access them. It helps businesses list their services on the Internet and guides users on accessing those services.
UDDI - Describing and finding web services. It's platform-independent, works with SOAP and WSDL, and serves as a distributed registry for web services.
SOAP web services - A way for programs to talk using XML. In Java, JAX-WS helps make these talks happen easily. It uses annotations to set up methods for communication.
