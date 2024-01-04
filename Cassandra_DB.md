# Cassandra Overview

Cassandra is a NoSQL distributed database known for its unique attributes:

- **Distributed Databases:** Cassandra databases are distributed, ensuring data distribution across multiple nodes.
- **Prevention of Data Loss:** The distribution mechanism acts as a safeguard against data loss resulting from hardware failure in any specific datacenter.
- **Scalability:** To leverage the full potential of Cassandra, it is recommended to run it on multiple machines, allowing for scalability and enhanced performance.
- **Node Communication:** Nodes in Cassandra communicate with each other using a protocol known as **gossip**. This protocol facilitates peer-to-peer communication among computers within the Cassandra cluster.

  ![image](https://github.com/Mostafahassen1/Hospital-System/assets/134046265/eb16dc2f-2f45-464c-8ef5-8d829da73fc0)

  ## Want more power? Add more nodes

One reason for Cassandra’s popularity is that it enables developers to scale their databases dynamically, using off-the-shelf hardware, with no downtime. You can expand when you need to – and also shrink


Perhaps you are used to Oracle or MySQL databases. If so, you know that extending them to support more users or storage capacity requires you to add more CPU power, RAM, or faster disks. Each of those costs a significant amount of money. And yet: Eventually you still encounter some ceilings and constraints.

![image](https://github.com/Mostafahassen1/Hospital-System/assets/134046265/c1cc2568-56bd-4c66-a4e7-beff60fedcd9)

% ## To double your capacity or double your throughput, double the number of nodes. That’s all it takes. Need more power? Add more nodes
