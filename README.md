# VPC-security-SG-NACL
Creating a custom VPC and two security groups. And will then launch EC2 instances and test connectivity using different protocols

# AWS Services Used: Amazon VPC, Amazon EC2
Architecture Diagram:
![image](https://github.com/user-attachments/assets/d0ea41f1-7f51-4637-aa4e-cdb10c1b6a91)


# Security Group and NACL (AWS)

In this project, I created a secure cloud environment using Amazon Web Services (AWS). The goal was to set up a private network where two virtual machines (EC2 instances) could communicate with each other while controlling the traffic that goes in and out of the network.

Here’s what I did:

* Created a Virtual Private Cloud (VPC): This is like creating a private network in the cloud where I could place my instances.

* Set up Security Groups and NACLs: These are like digital firewalls that control which types of internet traffic can reach the virtual machines. I customized these rules to allow safe communication between the two machines and block unwanted traffic.

* Deployed Two EC2 Instances: These are virtual servers that run applications. I set them up with a simple web server (Apache) so that they could serve a webpage.

* Tested Connectivity: I ensured that the machines could "talk" to each other by sending messages (pinging) and browsing the webpage from different machines. I also set up rules to restrict certain access, like allowing only my home IP to view one of the servers.

* The challenge was a hands-on way to learn how to secure cloud environments using AWS tools like VPC, Security Groups, and NACLs, while making sure everything works smoothly and safely.

* Finally tried setting and building up the same thing using Infrastructure as Code(IaC) with terraform.
