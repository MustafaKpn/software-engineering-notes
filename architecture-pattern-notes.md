## Microservices

### What is a Microservices Architecture?
Microservices is one of those architectural patterns which has emerged from the world of domain-driven design, continuous delivery, platfrom and infrastructure automation.

In the architecture of microservices, services can be developed, deployed and maintained independently. Each of these services is responsible for
discrete task and can communicate with other services through simple APIs to solve a larger complex business problem.

### Microservices Benefits

* Because the constituent services are small, they can be built by one or more small teams from the beginning separated by service boundaries
which make it easier to scale up the development.

* After development, deployed services can be scaled up independent of the whole application.
* Microservicese offer improved fault isolation. When an error happens in one of the services, the whole application doesn't necessarily stop functioning.
Similarly, when the error is fixed, it can be deployed only for the respective service instead of redeploying an entire application.

* Microservices architecture makes it easier to choose the technology stack which is best suited for the required service.
* Microservices architecture optimizes resource allocation and maintenance because teams work on small, well-defined services. Efforts are localized to specific services,
reducing overall development and system maintenance costs. 


### Disadvantages of microservices
* Increased complexity: microservices are distributed, which makes manging service communication challenging. 
* Debugging difficulties: It can be demanding to debug an application that contains multiple microservices, each with its own set of logs. 
* Data management challenges: Data consistency and transactions across multiple services can be complex. Microservices architecture calls for
careful data management and coordination to support data integrity.


### Where is microservices architecture used?
Microservices are used across a wide range of industries and applications due to their scalability and flexibility. Some cases and industries:
1. E-commerce
    * modular architecture for inventory, order management, payment and user accounts.
    * Handling high traffic during sales events.
    * Amazon uses microservices to handle the complex e-commerce ecosystem.

2. Financial Services
    * Payment gateways, fraud detection, and transcation processing.
    * Enabling faster development of banking features like loan applications or customer support bots.
    * PayPal uses microservices for their payment processing.
3. Internet of Things (IoT)
    * Device management, data collection, and real-time analytics.
    * Example: smart home platforms like Amazon Alexa.

4. Logistics and Supply Chain
    * Real-time tracking of shipments, inventory management, and order fulfillment.
    * Companies like FedEx and DHL adopt microservices for tracking and delivery systems.

### Microservices VS Monolith architectures
1. Structure
In microservices approach, an application is divided into small, independent services, each focusing on a specific functionality.
Whereas in monolith, an application is a single, unified codebase where all components are tightly coupled.

2. Scalability
In microservices, individual services can scale independently based on demand, making it more resource-efficient. Whereas using a monolith approach,
an entire application must scale as a whole, even if only a part of it experiences high demand.

3. Deploment
Microservices: services are deployed independently, enabling continuous deployment and rapid updates. Monolith: the entire application must
be redeployed for any change, increasing downtime and risk.

4. Fault isolation
Microservices: Failures in one service are isolated and don't affect the entire application.
Monolith: A failure in one component can potentially crash the entire application.

5. Technology stack
Microservices: Teams can use different technology stacks for different services, providing flexibility. Monolith: Entire application is built
using a single technology stack, simplifying development but limiting options.
