# Level 1-  Introduction to DEVOPS I


## Assessment :

Q1.What is your understanding of a DevOps Culture in an Organization ( Explain in not less than 500 words ) .

The word “DevOps” was coined in 2009 by Patrick Debois, who became one of its gurus. The term was formed by combining “development” and “operations,” which provides a starting point for understanding exactly what people typically mean when they say “DevOps.” Notably, DevOps isn’t a process or a technology or a standard. Many devotees refer to DevOps as a “culture”—a viewpoint that New Relic favors. We also use the term “DevOps movement” when talking about topics such as adoption rates and trends for the future, and “DevOps environment” to refer to an IT organization that has adopted a DevOps culture.

>“DevOps represents a change in IT culture, focusing on rapid IT service delivery through the adoption of agile, lean practices in the context of a system-oriented approach. DevOps emphasizes people (and culture), and seeks to improve collaboration between operations and development teams. DevOps implementations utilize technology— especially automation tools that can leverage an increasingly programmable and dynamic infrastructure from a life cycle perspective.”

>“A cornerstone of DevOps is continuous integration (CI), a technique designed and named by Grady Booch that continually merges source code updates from all developers on a team into a shared mainline. This continual merging prevents a developer’s local copy of a software project from drifting too far afield as new code is added by others, avoiding catastrophic merge conflicts.”


Q2. List and explain some of the IT tools you need to know to be a good DevOps engineer

- Git 

    Git is one of the most popular DevOps tools, widely used across the software industry. It’s a distributed SCM (source code management) tool, loved by remote teams and open source contributors. Git allows you to track the progress of your development work. You can save different versions of your source code and return to a previous version when necessary. It’s also great for experimenting, as you can create separate branches and merge new features only when they’re ready to go.

- Jenkins

    Jenkins is the go-to DevOps automation tool for many software development teams. It’s an open source CI/CD server that allows you to automate the different stages of your delivery pipeline. The main reason for Jenkins’ popularity is its huge plugin ecosystem. Currently, it offers more than 1,000 plugins, so it integrates with almost all DevOps tools, from Docker to Puppet.
    
-  Docker

    Docker has been the number one container platform since its launch in 2013 and continues to improve. It’s also thought of as one of the most important DevOps tools out there. Docker has made containerization popular in the tech world, mainly because it makes distributed development possible and automates the deployment of your apps. It isolates applications into separate containers, so they become portable and more secure. Docker apps are also OS and platform independent. You can use Docker containers instead of virtual machines such as VirtualBox.

-  Kubernetes 

    A Kubernetes cluster consists of one master and several worker nodes. The master node implements your pre-defined rules and deploys the containers to the worker nodes. Kubernetes pays attention to everything. For instance, it notices when a worker node is down and redistributes the containers whenever it’s necessary.

- Ansible

    Ansible is a configuration management tool, similar to Puppet and Chef. You can use it to configure your infrastructure and automate deployment. Its main selling points compared to other similar DevOps tools are simplicity and ease of use. Ansible follows the same Infrastructure As Code (IAC) approach as Puppet. However, it uses the super simple YAML syntax. With Ansible, you can define tasks in YAML, while Puppet has its own declarative language.

Q3. Draw up a Software development Life Cycle Identifying where DevOps fit in 


Q4.Draw up a DevOps process and explain what each represents 


# Level 2  - Introduction to DevOps II - Networking 

Q1 . Describe Hub, Switch and Router

- Hub
    A hub is the least intelligent of the three hardware devices. It serves as a connection point for the computers (and other devices such as printers) in a network. A hub simply passes along the traffic it receives to the computers connected to it. Any traffic that goes in one port comes out of the other ports. As a result, all the computers receive the traffic, even if it is not for them.

- Switch

    A switch is more intelligent than a hub. As a hub, a switch is the connection point for the computers (and other devices) in a network. However, a switch is more efficient at passing along traffic. It records the addresses of the computers connected to it in a table. When traffic comes through, the switch reads the destination address and sends that traffic to the appropriate computer rather than sending it to all the connected computers. If the destination address is not in the table, the switch sends the traffic to all the connected computers.

- Router 

    A router is the most intelligent of the three hardware devices. It is typically a small computing device designed specifically to understand, manipulate, and direct traffic. Routers include a user interface so that you can tell them where to direct the traffic.

    The primary function of a traditional router is to connect two or more networks (or network segments in a very large network) and direct traffic between them. For instance, a business might use a router to manage the connection between its local network and the Internet. To distribute the traffic to the computers in the local network, the business could connect the router to a switch or hub.

    While traditional routers are still available, most small business and home office routers today combine the functionality of a router and the functionality of a switch or hub in a single unit. These integrated routers often include additional software that lets businesses set up features such as network firewalls and virtual private networks. There are two main types of integrated routers: wired (e.g., for networks using Ethernet broadband) and wireless (e.g., for Wi-Fi networks).

Q2. What is the OSI model? 

The open systems interconnection (OSI) model is a conceptual model created by the International Organization for Standardization which enables diverse communication systems to communicate using standard protocols. In plain English, the OSI provides a standard for different computer systems to be able to communicate with each other.

The OSI Model can be seen as a universal language for computer networking. It’s based on the concept of splitting up a communication system into seven abstract layers, each one stacked upon the last.
    
 ![alt text](https://www.cloudflare.com/img/learning/ddos/what-is-a-ddos-attack/osi-model-7-layers.svg)
 
 Q3. What do you mean by the TCP/IP Model?
 
 TCP/IP Model helps you to determine how a specific computer should be connected to the internet and how data should be transmitted between them. It helps you to create a virtual network when multiple computer networks are connected together. The purpose of TCP/IP model is to allow communication over large distances.
 
 TCP/IP stands for Transmission Control Protocol/ Internet Protocol. TCP/IP Stack is specifically designed as a model to offer highly reliable and end-to-end byte stream over an unreliable internetwork.
 
 ![alt Tcp/ip model](https://cdn.guru99.com/images/1/093019_0615_TCPIPModelW1.png)
 
 Q4 . What do you mean by HTTP, TCP and UDP
 
    - TCP
    
        TCP/IP stands for Transmission Control Protocol/ Internet Protocol. It is specifically designed as a model to offer highly reliable and end-to-end byte stream over an unreliable internetwork.
        
    - UDP 
    
        UDP is a Datagram oriented protocol. It is used for broadcast and multicast type of network transmission. The full form of UDP is User Datagram Protocol (A datagram is a transfer unit associated with a packet-switched network.) The UDP protocol works almost similar to TCP, but it throws all the error-checking stuff out, all the back-and-forth communication and deliverability.
        
    - HTTP
        While TCP contains information about what data has or has not yet been received, HTTP contains specific instructions on how to read and process this data once it arrives. Before data is sent from one node on the Internet to another, it gets wrapped in information detailing the nature of the request being sent, or the response to said request. This is done using HTTP, or the Hypertext Transfer Protocol.

    When you type a URL into your web browser, you are sending an HTTP request to a web server. That server will then respond, again using the formatting of HTTP. (If you're wondering about HTTPS, which you might've noticed in front of most popular sites these days, the "S" stands for "secure"—meaning that those packets are encrypted.)

    The two most common examples of HTTP requests are: 1. "POST," denoting that this contains data to be pushed to the server 2. "GET," asking that a resource from the server be fetched

    So: TCP manages the data stream, and HTTP describes what the data in this stream contains.


Q5. What is a Firewall?

A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.

Firewalls have been a first line of defense in network security for over 25 years. They establish a barrier between secured and controlled internal networks that can be trusted and untrusted outside networks, such as the Internet. 

A firewall can be hardware, software, or both.

Q6 . Define Latency 
