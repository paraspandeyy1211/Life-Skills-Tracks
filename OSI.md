# OSI Model (Open Systems Interconnection)

OSI Model defines and is used to understand how data is transferred from one system to another over a network.
The OSI Model is a 7-layer conceptual framework developed by the International Organization for Standardization (ISO).


## Why does the OSI Model Exists

* It helps to make network communication standard so , everyone can follow the same rules.
* It makes finding and fixing problems in network easy.


## OSI Model Layers Overview
|Layer Number | Layer Name|
|-------------|-----------|
|7|Application Layer|
|6|Presentation Layer|
|5|Session Layer|
|4|Transport Layer|
|3|Network Layer|
|2|Data link Layer|
|1|Physical Layer|

---

## Layer 7: Application Layer

Application Layer is the top most layer of OSI Model.It produce the data to be transferred over the network. It acts as the interface between user application and the network

### Protocols
* FTP
* SMTP
* DNS
* Telnet
* HTTP
* HTTPS

### Functions
* Network Virtual Terminal (NVT): It allows a user to log on to a remote host.
* File Transfer Access and Management (FTAM): This application allows a user to access files in a remote host, retrieve files in a remote host, and manage or control files from a remote computer.
* Mail Services: Provide email service.
* Directory Services: This application provides distributed database sources and access for global information about various objects and services.



## Layer 6: Presentation Layer

Presentation Layer translates the data into a format that is understandable by the application layer


### Functions
* Translation: For example, ASCII to EBCDIC.
* Encryption/ Decryption: Data encryption translates the data into another form or code. The encrypted   data is known as the ciphertext, and decrypted data is called plain text
* Compression: Reduces the number of bits that is needed to be transmitted on the network.

---

## Layer 5: Session Layer

Session layer manages communication sessions between the applications.

### Functions 
* Session Control:Session layer allows established, manages and terminate a connection
* Synchronization: This layer allows a process to add checkpoints that are considered synchronization
  points in the data.
* Dialog Control: It controls whether communication is half-duplex or full-duplex.

### Example
* Maintaining an active video conferencing session

---

## Layer 4: Transport Layer

Transport Layer provides service to application layer and takes services from the network layer.

### Protocols
* TCP
* UDP

### Functions
* Segmentation and Reassembly: It breaks the data into segments and assemble them at the receiver.
* Service Point Addressing: It uses the port numbers to deliver data to the correct application.

### Example
* TCP used for file transfers
* UDP used for live-streaming

---

## Layer 3: Network Layer

The Network Layer works for the transmission of data from one host to the other located in different networks.


### Functions
*Routing: Finds the best path from source to destination.
*Logical Addressing: Adds IP addresses to identify devices uniquely.

### Protocols
* IPv4
* IPv6
* ICMP
* IPSec

### Devices
* Router

---

## Layer 2: Data Link Layer

Data Link layer is responsible for node-to-node data transfer

### Functions
* Framing: Breaks data into small frames so, that the receiver can understand it.
* Physical Addressing: It adds sender and receiver MAC addresses to each frame.
* Error Control: It also detects errors and requests retransmission if data is damaged or lost.
* Flow Control: Controls the speed of data transfer so, the receiver is not overloaded.
* Access Control: It also decides which device can use the shared communication channel at a time.

### Protocols
* Ethernet
* ARP
* PPP

### Devices
* Switch
* Bridge
* Network Interface Card

---

## Layer 1: Physical Layer

Physical layer is the lowest layer of OSI Model. It transmits raw bits over the physical medium.

### Functions
* Bit Synchronization: Keeps sender and receiver in sync using a clock.
* Bit Rate Control: Decides how many bits are sent per second.
* Physical Topology: Defines how devices are connected, like bus, star, or mesh.
* Transmission Mode: Specifies how data flows, such as simplex, half-duplex, or full-duplex.

### Examples
* Ethernet cables
* Fiber optic cables
* Wireless radio signals

---


## References

* https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/
* https://www.youtube.com/watch?v=vv4y_uOneC0"