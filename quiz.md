## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

-Service-oriented architecture (SOA) is a way of building software with reusable parts called services, like business building blocks that perform specific tasks.

2. List and discuss the characteristics of SOA.

Standardized Service Contracts - Services use contracts to describe what they do. This information is stored in a registry or profiles for easy understanding and finding.
Composability - Composability is breaking tasks into smaller, adaptable parts that work well together.
Interoperability - Interoperability ensures different services can work together smoothly with common rules, allowing easy access and use.
Loose Coupling – The goal is less dependence. Services have clear limits and fewer connections to be more independent and not rely heavily on each other.
Abstraction - It's about hiding the complicated details of how a service works, showing only what's necessary for others to connect. This simplicity keeps relationships flexible and easy to use together.
Service Reusability - It's breaking a big system into versatile parts for different uses, making the whole system more flexible and efficient.
Autonomy - It means each service operates independently, controlling its own actions without heavy reliance on others. This independence boosts reliability and predictability in how the service behaves.
Statelessness - It helps them grow and work better. By managing their 'state' in special ways, it makes their rules more flexible and easier to use again and again.
Discoverability - It's about easily finding services in a registry. Services communicate well and have individual or group management, not just as interchangeable tools.


3. Define Microservices.

-Microservices are like smaller, separate parts of a system, unlike big, connected systems. They make applications more flexible and easier to work with. They allow for specific updates, using different tools for different jobs, and can grow individually, saving money. They're different from big, connected systems and another similar system called service-oriented architecture.

4. List and discuss the benefits of using Microservices.

-Executives and project leaders like microservices because they align with how they want to organize teams and projects, matching the way operations are managed.

5. List and discuss the similarities and differences of SOA and Microservices.

-SOA connects services across the entire company, while microservices focus on one application, breaking it into flexible pieces. SOA aims for uniformity, while microservices allow individual communication methods. Both have strengths but serve different scopes in a business.

6. Define Web Services.

-A web service is an internet tool that lets different programs talk to each other by sharing data. It's like a language they all understand, making it easy for them to work together over the internet.

7. List and discuss the benefits of using Web Services.

Exposing the Existing Function on the network - A web service is a code that can be used online, letting other programs access and use your code's functions over the internet.
Interoperability - Web services connect apps, letting them share data and services across different technologies, like VB or .NET with Java web services, making them compatible across platforms.
Standardized Protocol - Web services use standardized protocols across layers for communication. This brings advantages like more choices, cost reduction through competition, and improved quality for businesses.
Low Cost Communication - Web services use cost-effective SOAP over HTTP, unlike pricier options like EDI/B2B. They can also run on reliable transport methods like FTP.

8. List and discuss the characteristics of Web Services.

XML-Based - Web services use XML for data, ensuring compatibility across networks and platforms. This makes web service applications highly interoperable.
Loosely Coupled - With a web service, you can make changes without affecting how you use it. But if it's closely tied, changes on one side mean changes on the other.
Coarse-Grained - It's best to have broad options for businesses. Web services naturally make these tools, ensuring they do the right job without being too detailed.
Ability to be Synchronous or Asynchronous - Synchronicity means the client is tied to the service's execution. In sync, the client waits for the service to finish before moving on.


9. List and discuss the distinct roles in Web Services Architecture.

Provider - The creator offers the web service for clients to use.
Requestor - A requestor is the client application seeking functionality through a web service, like .Net or Java apps.
Broker - The broker is the app that gives access to UDDI. UDDI helps the client app find the web service.

10. List and discuss the Web Services Components.

SOAP - A universal XML-based communication for computers, independent of operating systems and languages, and firewall-friendly.
WSDL -  Describes web services and how to access them. It helps businesses list their services on the Internet and guides users on accessing those services.
UDDI - Describing and finding web services. It's platform-independent, works with SOAP and WSDL, and serves as a distributed registry for web services.
SOAP web services - A way for programs to talk using XML. In Java, JAX-WS helps make these talks happen easily. It uses annotations to set up methods for communication.