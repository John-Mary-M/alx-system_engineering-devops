## 0x07. Networking basics #0

### OSI MODEL
The OSI (Open Systems Interconnection) model is a conceptual framework that
standardizes the functions of a communication system into seven different layers.
These layers help in understanding how data is transmitted over a network. The
layers, from bottom to top, are:

1. Physical Layer: Deals with the physical transmission of data through physical
media like cables, connectors, and network interfaces.
2. Data Link Layer: Provides reliable point-to-point data transfer between
network nodes, framing and error detection.
3. Network Layer: Handles routing and logical addressing to enable data transfer
between different networks.
4. Transport Layer: Ensures reliable and error-free end-to-end data delivery,
including segmentation, flow control, and error recovery.
5. Session Layer: Establishes, manages, and terminates connections between
applications, allowing them to communicate with each other.
6. Presentation Layer: Handles data formatting, compression, encryption, and
decryption, ensuring that data is presented in a compatible format.
7. Application Layer: Provides services directly to the end-user applications,
such as email, file transfer, and web browsing.

The OSI model serves as a reference for understanding network protocols and
their interactions in a layered manner.

### LAN
LAN stands for Local Area Network. It is a network infrastructure that is
typically confined to a small geographical area, such as an office building,
school, or home. LANs are used to connect computers, devices, and resources
within a limited area to facilitate communication and resource sharing.
 Typical usage of LANs includes:
 1. File and Printer Sharing: LANs allow users to share files and printers among
connected devices, making it easier to collaborate and access shared resources.
 2. Internet Connectivity: LANs provide a means to connect devices to the
 internet through routers or gateways, allowing users to access online services
 and communicate with the outside world.
 3. Local Application Access: LANs enable users to access applications and
 databases hosted on local servers, improving efficiency and reducing network
 traffic.
 4. Gaming and Entertainment: LANs are commonly used for local multiplayer
 gaming, streaming media, and sharing entertainment content within a limited
 group of users.
 The typical geographical size of a LAN can vary, but it is generally limited
 to a few hundred meters to a few kilometers. LANs are designed to cover a small
 area and provide high-speed and reliable connectivity within that area.


### WAN
WAN stands for Wide Area Network. It is a network infrastructure that spans
large geographical areas, connecting multiple LANs or other networks together.
WANs are used to facilitate communication and data transfer over long distances,
often across different cities, countries, or even continents.
Typical usage of WANs includes:
1. Interconnecting Branch Offices: WANs enable organizations to connect their
branch offices located in different geographic locations, allowing for seamless
communication, resource sharing, and centralized management.
2. Internet Connectivity: WANs provide connectivity to the internet for users in
various locations, enabling access to online services, cloud resources, and
global communication.
3. Data Transfer and Replication: WANs are used to transfer and replicate data
between different data centers or remote locations, ensuring data redundancy,
disaster recovery, and efficient data distribution.
4. Wide-scale Collaboration: WANs facilitate collaboration between
geographically dispersed teams by providing a platform for real-time
communication, video conferencing, and shared access to documents and
applications.
The typical geographical size of a WAN can vary significantly, ranging from
regional networks covering a few hundred kilometers to global networks spanning
continents. WANs utilize various technologies such as leased lines, MPLS
(Multiprotocol Label Switching), and VPNs (Virtual Private Networks) to
establish connectivity over long distances.

### The Internet
a unique string of characters that identifies each computer using the Internet
Protocol to communicate over a network.
There are 2 types of IP addresses name;
Private IP Addresses. The devices you connect to the internet network are all
associated with the IP address, including laptops, computers, smartphones, etc.

Public IP Addresses. The public IP address acts as a whole primary address that
contains all the other network devices associated with the network. Each device
in the network is assigned its private IP address. The Internet Service Provider
(ISP) supervises the assignment of the public IP address to the network device
(router). ISPs accumulate a large number of IP addresses that they assign to
their clients.

SUBNET: A subnet, or subnetwork, is a segmented piece of a larger network. More
specifically, subnets are a logical partition of an IP network into multiple,
smaller network segments.

### TCP/ UDP:
The main difference between TCP (transmission control protocol) and UDP (user
datagram protocol) is that TCP is a connection-based protocol and UDP is
connectionless. While TCP is more reliable, it transfers data more slowly. UDP
is less reliable but works more quickly.

A port in networking is a software-defined number associated to a network
protocol that receives or transmits communication for a specific service

SSH port number: 22
HTTP port number: 80
HTTPS port number: 443