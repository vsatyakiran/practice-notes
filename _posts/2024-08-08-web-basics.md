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
