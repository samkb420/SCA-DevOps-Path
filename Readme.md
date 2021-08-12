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


