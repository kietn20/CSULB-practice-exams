# Introduction to Networks & Distributed Computing - Practice Questions

1. What are the two main functions of a router?

A) Forwarding and filtering
B) Routing and switching
C) Forwarding and routing
D) Switching and filtering

Solution: <details><summary>Click to reveal</summary>C) Forwarding and routing</details>

2. In the context of routing, what does "forwarding" refer to?

A) Planning a trip from source to destination
B) Moving packets from router's input to appropriate router output
C) Determining the best path through the network
D) Updating the routing table

Solution: <details><summary>Click to reveal</summary>B) Moving packets from router's input to appropriate router output</details>

3. What does a routing protocol aim to determine?

A) The fastest path through the network
B) The most secure path through the network
C) The path with the highest bandwidth
D) The "good" path, typically meaning minimum link cost path

Solution: <details><summary>Click to reveal</summary>D) The "good" path, typically meaning minimum link cost path</details>

4. Which of the following is NOT a classification of routing?

A) Static
B) Dynamic
C) Hybrid
D) Intradomain

Solution: <details><summary>Click to reveal</summary>C) Hybrid</details>

5. What is a characteristic of static routing?

A) Routes are discovered automatically
B) Network administrator configures the routes
C) Routes change based on network conditions
D) Routing tables are updated periodically

Solution: <details><summary>Click to reveal</summary>B) Network administrator configures the routes</details>

6. Which of the following is a dynamic intradomain routing protocol?

A) BGP
B) TCP
C) OSPF
D) HTTP

Solution: <details><summary>Click to reveal</summary>C) OSPF</details>

7. What is the main idea behind the distance vector routing algorithm?

A) Each node has complete information about the network topology
B) Each node only knows about its directly connected neighbors
C) Each node has information about the cost to all other nodes and distributes this to immediate neighbors
D) Each node floods the network with link-state packets

Solution: <details><summary>Click to reveal</summary>C) Each node has information about the cost to all other nodes and distributes this to immediate neighbors</details>

8. What is the "count to infinity" problem in distance vector routing?

A) When the hop count exceeds the maximum allowed value
B) When routers continuously increment the hop count due to outdated information
C) When the routing table becomes too large to process
D) When the network has too many routers to converge

Solution: <details><summary>Click to reveal</summary>B) When routers continuously increment the hop count due to outdated information</details>

9. What is the purpose of the "split horizon" technique in routing?

A) To increase the speed of routing updates
B) To prevent routing loops
C) To reduce the size of routing tables
D) To enable load balancing

Solution: <details><summary>Click to reveal</summary>B) To prevent routing loops</details>

10. What is the maximum hop count in RIP (Routing Information Protocol)?

A) 8
B) 15
C) 16
D) 32

Solution: <details><summary>Click to reveal</summary>C) 16</details>

11. Which routing method sends information about directly connected links to all nodes in the network?

A) Distance Vector
B) Link State
C) Path Vector
D) Hierarchical

Solution: <details><summary>Click to reveal</summary>B) Link State</details>

12. What algorithm is commonly used in link-state routing to compute the shortest path?

A) Bellman-Ford algorithm
B) Dijkstra's algorithm
C) Floyd-Warshall algorithm
D) Kruskal's algorithm

Solution: <details><summary>Click to reveal</summary>B) Dijkstra's algorithm</details>

13. What is an Autonomous System (AS) in the context of internet routing?

A) A set of routers under a single technical administration
B) A group of computers in a local area network
C) A collection of routing protocols
D) A type of routing algorithm

Solution: <details><summary>Click to reveal</summary>A) A set of routers under a single technical administration</details>

14. Which protocol is used for routing between Autonomous Systems?

A) RIP
B) OSPF
C) BGP
D) EIGRP

Solution: <details><summary>Click to reveal</summary>C) BGP</details>

15. What is a stub AS?

A) An AS that has connections to multiple other ASes
B) An AS that allows transit traffic
C) An AS that has only a single connection to one other AS
D) An AS that uses only static routing

Solution: <details><summary>Click to reveal</summary>C) An AS that has only a single connection to one other AS</details>

16. What is the primary objective of BGP (Border Gateway Protocol)?

A) Performance optimization
B) Security enhancement
C) Reachability
D) Load balancing

Solution: <details><summary>Click to reveal</summary>C) Reachability</details>

17. How do BGP peers exchange routing information?

A) Over UDP connections
B) Over TCP connections
C) Using link-state packets
D) Through distance vector updates

Solution: <details><summary>Click to reveal</summary>B) Over TCP connections</details>

18. What port number does BGP use for its connections?

A) 80
B) 443
C) 53
D) 179

Solution: <details><summary>Click to reveal</summary>D) 179</details>

19. Which of the following is NOT a type of Autonomous System?

A) Stub AS
B) Multihomed AS
C) Transit AS
D) Core AS

Solution: <details><summary>Click to reveal</summary>D) Core AS</details>

20. What is the purpose of Autonomous System Numbers (ASN)?

A) To identify individual routers within an AS
B) To assign IP addresses to devices in the AS
C) To exchange exterior routing information and identify the AS itself
D) To determine the geographic location of the AS

Solution: <details><summary>Click to reveal</summary>C) To exchange exterior routing information and identify the AS itself</details>