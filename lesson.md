## Brief

### Preparation

Write about any preparations needed for the lesson, such as tools, installations, prior-knowledge, etcs.

### Lesson Overview

Write about how instructors can brief the students at the start of the lesson. It is good to guide students through what is going to be covered and the outcome. Setting expectations.

---

## Part 1 - Server?

The term ‘server’ has a double meaning in IT. It is used to describe a computer that makes resources available over a network, as well as the program that runs on this computer. So it’s necessary to have two different server definitions:


**Definition Server (hardware):** a hardware-based server is a physical device connected to a computer network on which one or more software-based servers run alongside the operating system. An alternative term for a hardware-based server is host. In principle, any computer can be used as a host with server software.

**Definition Server (software):** a software-based server is a program that offers a specialized service to be used by other programs (known as clients) locally or via a network. The service offered depends on the type of server software. The client-server model is the basis of communication. When it comes to exchanging data, service-specific communication protocols are used.


### How do servers work?

Server services operating via computer networks are realized thanks to the help of client server-models. This concept makes it possible to divide tasks among different computers and allow users access to them simultaneously. Every service provided via a network requires a server (software), which is permanently on standby. This is the only way to ensure that clients, like web browsers or e-mail programs, always have the opportunity to access the server and utilize its service when needed.


![image](https://user-images.githubusercontent.com/106639884/184091869-f35d6b1b-5012-4bb3-83b1-b277d212aeb8.png)


---

## Part 2 - Types of servers

Though several technical specifications distinguish servers, generally, these high-powered machines can be broken down by functionality or their dedicated role(s) for an organization and by form factor.


### By Server Functionality

Different types of servers play one or multiple jobs, from serving email and multimedia content to protecting internal networks and hosting web applications. The most common types of functionality include servers for shared network files, databases, proxy security, email, and server backups.

Here are many types of servers that all perform different functions.


**1. File servers**

File servers store and distribute files. Multiple clients or users may share files stored on a server. In addition, centrally storing files offers easier backup or fault tolerance solutions than attempting to provide security and integrity for files on every device in an organization. File server hardware can be designed to maximize read and write speeds to improve performance.

**2. Print servers**

Print servers allow for the management and distribution of printing functionality. Rather than attaching a printer to every workstation, a single print server can respond to printing requests from numerous clients. Today, some larger and higher-end printers come with their own built-in print server, which removes the need for an additional computer-based print server. This internal print server also functions by responding to print requests from a client.

**3. Application servers**

Application servers run applications in lieu of client computers running applications locally. Application servers often run resource-intensive applications that are shared by a large number of users. Doing so removes the need for each client to have sufficient resources to run the applications. It also removes the need to install and maintain software on many machines as opposed to only one.

**4. DNS servers**

Domain Name System (DNS) servers are application servers that provide name resolution to client computers by converting names easily understood by humans into machine-readable IP addresses. The DNS system is a widely distributed database of names and other DNS servers, each of which can be used to request an otherwise unknown computer name. When a client needs the address of a system, it sends a DNS request with the name of the desired resource to a DNS server. The DNS server responds with the necessary IP address from its table of names.

**5. Mail servers**

Mail servers are a very common type of application server. Mail servers receive emails sent to a user and store them until requested by a client on behalf of said user. Having an email server allows for a single machine to be properly configured and attached to the network at all times. It is then ready to send and receive messages rather than requiring every client machine to have its own email subsystem continuously running.

**6. Web servers**

One of the most abundant types of servers in today’s market is a web server. A web server is a special kind of application server that hosts programs and data requested by users across the Internet or an intranet. Web servers respond to requests from browsers running on client computers for web pages, or other web-based services. Common web servers include Apache web servers, Microsoft Internet Information Services (IIS) servers and Nginx servers.

**7. Database servers**

The amount of data used by companies, users, and other services is staggering. Much of that data is stored in databases. Databases need to be accessible to multiple clients at any given time and can require extraordinary amounts of disk space. Both of these needs lend themselves well to locating such databases on servers. Database servers run database applications and respond to numerous requests from clients. Common database server applications include Oracle, Microsoft SQL Server, DB2, and Informix.

**8. Proxy servers**

A proxy server acts as an intermediary between a client and a server. Often used to isolate either the clients or servers for security purposes, a proxy server takes the request from the client. Instead of responding to the client, it passes the request on to another server or process. The proxy server receives the response from the second server and then replies to the original client as if it were replying on its own. In this way, neither the client nor the responding server needs to directly connect to each other.

**9. Monitoring and management servers**

Some servers exist to monitor or manage other systems and clients. There are many types of monitoring servers. Several of them listen to the network and receive every client request and server response, but some do not request or respond to data themselves. In this way, the monitoring server can keep track of all the traffic on the network, as well as the requests and replies of clients and servers, without interfering with those operations. A monitoring server will respond to requests from monitoring clients such as those run by network administrators watching the health of the network.


### By Form Factor

![image](https://user-images.githubusercontent.com/106639884/183854053-24afc7d7-6d38-463d-89a4-9960a154b5ba.png)


1. Blade Servers

Blade servers offer the densest build with a circuit board enclosure that requires minimal cabling and maintenance.


2. Rack Servers

Rack servers are mountable and less dense but ideal for SMB to enterprise organizations that can manage ongoing maintenance.

3. Tower Servers

Tower servers are a vertical, standalone enclosure and least dense with low maintenance and ideal for smaller organizations and teams.

---

## Part 3 - Server Virtualization

Server virtualization is the process of using software to divide physical hardware into separate unique virtual servers. Once divided, these independent virtual servers can be used for a multitude of tasks. Each virtual server will be able to host a different operating system without any compatibility issues. 

### Types of Server Virtualization

There are three main types of server virtualization: full-virtualization, para-virtualization, and OS-level virtualization.

**Full-Virtualization**

A hypervisor is a specialized type of software that is necessary for full server virtualization. There are many different hypervisors available, so make sure to compare your requirements with available features before finalizing a purchase. Hypervisors function by communicating with servers to monitor disk space and CPU usage. The software can then allocate resources as needed across multiple virtual server deployments. Computing power can even be shared across various operating systems with ease without sacrificing efficiency. Hypervisors do require a set amount of dedicated server resources to operate, limiting overall server power. When utilizing full virtualization, the separate server instances will not need to be aware of each other.

**Para-Virtualization**

The major difference between full and para-virtualization is that each OS on the server is aware of each other's presence. This allows for an entire network to work together to manage resources. The most significant benefit of para-virtualization is that the hypervisor doesn't require nearly as many resources to operate because different virtual servers are aware of each other and thus can more efficiently share physical resources.  

**OS-Level Virtualization**

The most basic form of server virtualization is OS-level virtualization. There are limitations when using this method, but it can be implemented and maintained with fewer resources than para- or full- virtualization. When using OS-level virtualization, there is no need for a hypervisor. The duty of managing resources and separating virtual machines is instead handled by the physical server’s operating system. The drawback to this solution is that each virtual machine will have to run the same operating system, because the OS is acting as a hypervisor. 
