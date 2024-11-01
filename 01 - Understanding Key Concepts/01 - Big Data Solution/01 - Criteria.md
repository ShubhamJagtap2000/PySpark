1. Scalability: Ability of a system to increase or decrease performance in response to demand

   - **Vertical scaling**
     - Using a bigger machine(or server) to handle more requests
     - Adding more resources to the existing machine(monolithic approach)
     - Complex scaling method
     - No load balancing is required
     - Single point of failure(if main server is failed, then the whole system is down)
     - Inter-process communication(faster network)
     - Data is consistent(no data transaction)
     - Hardware limitations
   - **Horizontal scaling**
     - Adding new machines(or servers) to the cluster(system)
     - Easier to implement and use in distributed systems
     - Requires load-balancing
     - Resilient system
     - Remote processing calls(communication between the sub-systems network)
     - Data is not consistent(needs maintenance)
     - No hardware limitations
     - Scales well when the number of requests increases

2. Fault Tolerance:
   - A distributed system is more fault-tolerant as it avoids a single point of failure. It is highly available and cost-effective.
   - A monolithic system is not fault-tolerant as the system fails if the server is down. It is not highly available and is costly.
      
