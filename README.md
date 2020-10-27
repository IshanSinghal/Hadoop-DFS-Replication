# Hadoop-DFS-Replication

 Setup a Hadoop cluster with one NameNode(Master) and 4 DataNodes(Slave) and one Client Node. ✴️ Upload a file through client to the NameNode. ✴️ Check which DataNode the Master chooses to store the file. ✴️ Once uploaded try to read the file through Client using the cat command and while Master is trying to access the file from that DataNode where it stored the file delete that DataNode or crash it and see with help of the replicated storage how master retrieves the file and present it to client.

https://www.linkedin.com/pulse/replication-hadoop-ishan-singhal/

REPLICATION IN HADOOP DFS for a fault tolerance setup.

What is replication and why is it needed?

How is replication done?

What happens when a DataNode crashes during Node?

![Concept](https://github.com/IshanSinghal/Hadoop-DFS-Replication/blob/main/REPLICAS.png)

![Concept](https://github.com/IshanSinghal/Hadoop-DFS-Replication/blob/main/diagram.jpg)
