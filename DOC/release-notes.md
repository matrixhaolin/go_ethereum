This is a POC release (version 0.01) for Consensus Algoritm, introducing modular designs as regards the node election, data synchronization as well as broadcasting through P2P network.

Node Election + Data Synchronization
When a miner/verification node is elected, it will synchronize data to other nodes in its group via a TCP connection

Broadcasting
Once mining is completed on one node, it will connect to the other nodes to transfer the information of the new block. After the master node receives it, the new block will become part of the chain

AI
The codes designed for AI features will be implemented via ASIC chips controlled by RTL codes. Those RTL codes could be translated into C++ codes later, which can be simulated running on all PCs, but runnnig speeds vary depending on the performance of each PC. Purpose-build hardware will be announced in the future.

Crytograph
More powerful crytographic methods have been introduced in this release to bring higher security.

Credits
=======
+Thanks to everyone who directly contributed to this release:
  
- Bill Lee
- Yanqiang Lee
- Xuyang Wang
- Cao Ao
- Xuelong Sun
- Zheng He
- Shaoqing Long
- Allen Hao

  
+And all those who contributed additional code review and/or security research:
+- 
 