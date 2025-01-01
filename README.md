# AuroraKeyDB - Distributed Key-Value Store 
- Check the project progress here - https://github.com/vishwamshukla/distributed-kvstore

## Overview

AuroraKeyDB is a high-performance distributed key-value store designed for handling millions of transactions per second (TPS). It is built using modern technologies like **Java**, **Spring Boot**, **Redis**, **gRPC**, **Kafka**, and **RxJava**, ensuring scalability and fault tolerance. This system leverages **replication**, **consistent hashing**, and **leader election** to achieve high availability. The application integrates **Grafana**, **InfluxDB**, **Datadog** for monitoring and observability, and includes **JUnit** for load testing.

---

## Technologies Used

- **Backend**: Java, Spring Boot, Redis, gRPC, Kafka, RxJava
- **Frontend**: Angular
- **Database**: Redis (for caching)
- **Monitoring**: Grafana, InfluxDB, Datadog
- **Testing**: JUnit for load testing
- **Version Control**: GitHub
- **Cloud**: Docker, Kubernetes for containerization

---

## Architecture

1. **Distributed Key-Value Store**:
   - **Redis** is used for **caching** high-frequency data, ensuring low latency and high throughput.
   - **Kafka** provides an event streaming platform for handling real-time data streams.
   - **gRPC** is utilized for efficient communication between microservices.
   - **RxJava** is used for reactive programming, enabling **asynchronous data processing** and improving performance by handling multiple concurrent operations.

2. **Scalability & Fault Tolerance**:
   - **Replication** ensures that the data is duplicated across multiple nodes for fault tolerance.
   - **Consistent Hashing** ensures that the data is evenly distributed across nodes.
   - **Leader Election** is implemented to ensure that only one node can coordinate the partitioning of the data, preventing conflicts.

3. **Monitoring and Observability**:
   - **Grafana** is used to visualize real-time metrics collected from **InfluxDB**.
   - **Datadog** is integrated for system-wide monitoring, alerting, and performance tracking.

4. **Frontend**:
   - The front-end is built using **Angular**, which interacts with the back-end APIs for visualizing data and managing user requests.

---
