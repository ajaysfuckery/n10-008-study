# Peer to Peer or Client-Server?
<hr>
- There are two main networks you need to know about:
	- Peer-to-peer
	- Client-Server

#### Peer to peer networks
<hr>
- Computers connected together in a peer to peer network do not have any central or special authority -- they're all peers, meaning that when it comes to authority, they're all equals. The authority to perform a security check for proper access rights lies with the computer that has the desired resource being requested from it.

- It also means that the computers co-existing in a peer to peer network can be client machines that access resources and server machines provide those resources to other computers.

- This type of network works very well, as long as there aren't many computers connected to the network, users back up data locally and there isn't much of a need for network security.

- If your network is running Windows, macOS or Linux in a local LAN workgroup, you have a peer to peer network.

- Peer to peer networks definitely present some security challenges and backing up data can get sketchy!

- Backing up data in a peer to peer network is essential

- Because security on a peer to peer network is not centrally governed, each and every user has to rememeber and maintain a list of users and passwords on each and every machine. Worse, some of these all-important passwords for the same users change on different machines--even for accessing different resources.

##### Client-Server Networks
<hr>
- Client-Server networks are the *polar opposite* of peer to peer networks because in them, a single server uses a network operating system for managing the whole network.

- How it works:
	1. A client machine's request for a resource goes to the main server, which responds by handling the security and directing the client to the desired resource. This happens instead of the request going directly to the machine with the desired resource and it has some serious advantages.

	2. First because the network is much better organized and doesn't depend on users remembering where needed resources are, it is a whole lot easier to find the files you need because everything is stored in one spot. On the Server itself. Your security also gets tighter becuase all usernames and passwords are stored on that server, which is never used as a workstation.
	
	3. You even gain scalability--client-server networks can have legions of workstations on them. And surprisingly with all those demands, the network's performance is even optimized

- Most of todays networks are a healthy blend of peer to peer and client-server architectures, with carefully specified servers that permit the simultaneous sharing of resources from devices runnning workstation operating system.
- Even though the supporting machines can't handle as many inbound connections at a time, they still run the server service reasonably well. And if this type of mixed environment is designed well, most networks benefit greatly by having the capacity to take advantage of the positive aspects of both worlds.