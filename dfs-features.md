# DFS feautres


### Transparency
Transparency refers to hiding details from a user. The following types of transparency are 
desirable.
- Structure transparency: Multiple file servers are used to provide better performance, 
scalability, and reliability. The multiplicity of file servers should be transparent to the client of a 
distributed file system. Clients should not know the number or locations of file servers or the 
storage devices instead it should look like a conventional file system offered by a centralized, 
time sharing operating system.
ii. 
- Access transparency: Local and remote files should be accessible in the same way. The file 
system should automatically locate an accessed file and transport it to the client’s site.
iii. 
- Naming transparency: The name of the file should not reveal the location of the file. The 
name of the file must not be changed while moving from one node to another.
iv. 
- Replication transparency: The existence of multiple copies and their locations should be 
hidden from the clients where files are replicated on multiple nodes.

### User mobility
The user should not be forced to work on a specific node but should have the flexibility to work 
on different nodes at different times. This can be achieved by automatically bringing the users 
environment to the node where the user logs in.
### Performance
Performance is measured as the average amount of time needed to satisfy client requests, which 
includes CPU time plus the time for accessing secondary storage along with network access 
time. Explicit file placement decisions should not be needed to increase the performance of a 
distributed file system.
### Simplicity and ease of use
User interface to the file system be simple and number of commands should be as small as 
possible. A DFS should be able to support the whole range of applications.
### Scalability
A good DFS should cope with an increase of nodes and not cause any disruption of service. 
Scalability also includes the system to withstand high service load, accommodate growth of users 
and integration of resources.
### High availability
A distributed file system should continue to function even in partial failures.
### High reliability
Probability of loss of stored data should be minimized. System should automatically generate 
backup copies of critical files in event of loss.
### Data integrity
Concurrent access requests from multiple users who are competing to access the file must be 
properly synchronized by the use of some form of concurrency control mechanism. Atomic 
transactions can also be provided to users by a file system for data integrity.
### Security
A distributed file system must secure data so that its users are confident of their privacy. File 
system should implement mechanisms to protect data that is stored within.
### Heterogeneity
Distributed file system should allow various types of workstations to participate in sharing files 
via distributed file system. Integration of a new type of workstation or storage media should be 
designed by a DFS.
