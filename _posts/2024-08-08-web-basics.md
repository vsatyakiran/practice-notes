---
title: "Web Basics"
date: 2024-08-08
categories:
---

## Horizontal Scaling vs Vertical Scaling

- **Horizontal Scaling (Scaling in)**: Adding more machines to your pool of resources. Increasing the number of machines in your network. Single point of failure is less likely to occur.

  - **Load Balancer**: Distributes incoming network traffic across multiple servers.

  - **Caching**: Storing data in a cache to reduce the load on the primary data source.

  - **Database Sharding**: Breaks up a database into smaller, more manageable parts.

  - **Replication**: Copying data from one database to another.

  - **Microservices**: Architectural style that structures an application as a collection of services.

  - **Containerization**: OS-level virtualization method used to deploy and run distributed applications without launching an entire VM for each app.

  - **Serverless**: Cloud computing model where a cloud provider dynamically manages the allocation of machine resources.

  - **Content Delivery Network (CDN)**: System of distributed servers that deliver web content to a user based on the geographic locations of the user, the origin of the webpage, and a content delivery server.

  - **Distributed File System**: Allows multiple users to access the same file or directory of files.

- **Vertical Scaling (Scaling up)**: Adding more power (CPU, RAM, etc) to an existing machine. Increasing the capacity of a single machine. Single point of failure is likely to occure.


# Authentication vs Authorization

**Authentication:** Determines whether a user is who they claim to be. It verifies the identity of a user, device, or service, ensuring that only authorized entities can access a system or resource. Authentication typically involves:

Challenges (e.g., username and password, biometric data, one-time pins)

Verification of credentials (e.g., password, fingerprint, facial recognition)

Confirmation of identity (e.g., user account validation)

**Authorization:** Determines what actions a user can perform or what resources they can access once their identity has been verified. It grants or denies permissions based on predefined rules, roles, or access controls. Authorization ensures that even if an attacker gains access to a system, they will not be able to access sensitive data or perform unauthorized actions.

# SDK vs API

**SDK (Software Development Kit):** A set of tools, libraries, and documentation that developers use to build applications for a specific platform or framework (A software development kit (SDK) is a collection of software development tools in one installable package). SDKs provide prebuilt components, sample code, and other resources to help developers create software that integrates with a particular system or service. SDKs are typically platform-specific and may include:

  - Libraries
  - APIs
  - Code samples
  - Documentation
  - Tools (e.g., compilers, debuggers)

**API (Application Programming Interface):** A set of rules and protocols that allow different software applications to communicate with each other. APIs define the methods and data formats that applications can use to interact with each other, enabling developers to access the functionality of a system or service without needing to understand its internal workings. APIs can be used to:

  - Retrieve data
  - Send data
  - Perform actions
  - Integrate with third-party services
  - Extend the functionality of an application


# Stateless vs Stateful

**Stateless:** In a stateless system, each request from a client to a server must contain all the information necessary to understand the request. The server does not store any client state between requests. This approach simplifies server design and scalability, as any server can handle any request from any client. However, it can lead to increased network traffic and slower response times, as the client must provide all necessary information with each request.

**Stateful:** In a stateful system, the server maintains client state between requests. This allows the server to remember information about the client, such as session data, preferences, or authentication status. Stateful systems can provide a more personalized and efficient user experience, as the server can tailor responses based on the client's state. However, stateful systems can be more complex to design and scale, as servers must manage and synchronize client state across multiple requests.
