# Leveraging Cloudfront For high-Performance Static Website Hosting Whether With Amazon S3 or Independently
# Overview:
To launch a static website without using Amazon S3 via CloudFront, EC2 and ELB services and to launch a website using Amazon S3 bucket via Cloudfront in the AWS console .
# Description:
**Case 1** :Using Amazon EC2 instances as the hosting infrastructure, Amazon CloudFront for content distribution, and an Elastic Load Balancer (ELB) for dividing up incoming traffic across several EC2 instances comprise the stages involved in launching a website without utilizing Amazon S3.

**Case 2:** :Using Amazon S3 for storing the files which are used to host a static website(Amazon S3 is used to store the static files (HTML, CSS, JavaScript, images, etc.) and Amazon CloudFront for content distribution.
# Prerequisites:
**We must have some basic knowledge on:**

**1.	Amazon EC2 (Elastic Compute Cloud) :** Web service which provides scalable computing capacity in the cloud.

**Instance -** Virtual computing environments.

**2.	Amazon CloudFront :** It is an Content Delivery Network (CDN) service, which is provided by Amazon Web Services, which helps to distribute content with low latency and high data transfer speeds, which improves application performance.
 
**3.	Elastic Load Balancing :** It is a service which is provided by Amazon in which the incoming traffic is efficiently distributed across a group of servers to increase the speed and performance of those servers.

- **Classic Load Balancers -** An older type of load balancer works on Application Layer-7 and Transport Layer-4 of Open System Interconnection (OSI) model.

- **Application Load Balancers :** An updated version of classic load balancer also called as version 2, which works on Application Layer-7 of Open System Interconnection (OSI) model. Layer-7 accepts the protocols of HTTP/HTTPS.

- **Network Load Balancers :** A type of load balancer which works on Transport Layer-4 of Open System Interconnection (OSI) model. Layer-4 accepts the protocols of TCP/UDP. When an application requires traffic with high performance and low latency then we use Application Load Balancing.

- **Gateway Load Balancers :** A type of load balancer enables you to deploy, scale, and manage virtual appliances in Amazon Web Services such as, Firewalls, Intrusion Detection and prevention systems, Deep packet inspection systems at your network layer. Gateway Load Balancer works on Network Layer-3 of Open System Interconnection (OSI) model.

**4. Amazon S3(Simple Storage Service) :** Amazon S3 which is a simple storage service which is provided by Amazon Web Service which is a Cloud service provider, S3 is a Scalable storage service which is object level storage that offers scalability, data availability, security, and performance. We can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.
 
**Case 1: Using Amazon EC2 instances as the hosting infrastructure, Amazon CloudFront for content distribution, and an Elastic Load Balancer (ELB) for dividing up incoming traffic across several EC2 instances comprise the stages involved in launching a website without utilizing Amazon S3.**
<img width="769" height="468" alt="1" src="https://github.com/user-attachments/assets/9d147336-5a5b-4ae4-a67a-402340bdf798" />

