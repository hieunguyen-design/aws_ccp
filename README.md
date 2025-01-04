# NOTE

## What is the server composed of
* CPU + RAM
* Storage: data
* Database: Store data in a structed way
* Network: Routers, switch, DNS server
## IT Terminilogy
* Network: cabels, routers and setver connected with each other
* Router: a networking device that forwards data packets between computer networks. They know where to send your packets on the internet!
* Switch: Takes a packet and send it to the correct server / client on your network. 

## The Deployment Models of the Cloud
### Private Cloud
* Cloud services used by a single organization, not exposed to the public. 
* Complete control 
* Security for sensitive applications 
* Meet specific business needs
### Public Cloud
* Cloud resources owned and operated by a thirdparty cloud service provider delivered over the Internet.
* Six Advantages of Cloud Computing
### Hybrid Cloud
* Keep some servers on premises and extend some capabilities to the Cloud
* Control over sensitive assets in your private infrastructure
* Flexibility and costeffectiveness of the public cloud

## The Five Characteristics of Cloud Computing NOT FOR DISTRIBUTION
* On-demand self service:
  * Users can provision resources and use them without human interaction from the service provider
*  Broad network access:
  * Resources available over the network, and can be accessed by diverse client platforms
* Multi-tenancy and resource pooling:
  * Multiple customers can share the same infrastructure and applications with security and privacy
  * Multiple customers are serviced from the same physical resources
* Rapid elasticity and scalability:
  * Automatically and quickly acquire and dispose resources when needed
  * Quickly and easily scale based on demand
 * Measured service:
   * Usage is measured, users pay correctly for what they have used
## Types of Cloud Computing
* Infrastructure as a Service (IaaS):
  * Amazon EC2 (on AWS)
  * GCP, Azure, Rackspace, Digital Ocean, Linode
* Platform as a Service (PaaS)
  * Elastic Beanstalk (on AWS)
  * Heroku, Google App Engine (GCP), Windows Azure (Microsoft)
* Software as a Service (SaaS)
  * Many AWS services (ex: Rekognition for Machine Learning)
  * Google Apps (Gmail), Dropbox, Zoom
## Pricing of the Cloud 

pay-as-you-go pricing model
* Compute
* Storage
* Data transfer OUT of the Cloud

## AWS Global Infrastructure
* **AWS Regions**
  * AWS has Regions all around the world
  * Names can be us-east-1, eu-west-3…
  * AWS Regions consist of multiple, isolated, and physically separate Availability Zones within a geographic area.
  * Most AWS services are region-scoped
* **AWS Availability Zones**
  * Each region has many availability zones (usually 3, min is 3, max is 6). Example: ap-southeast-2a, ap-southeast-2b, ap-southeast-2c
  * Each availability zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity
  * They’re separate from each other, so that they’re isolated from disasters
  * They’re connected with high bandwidth, ultra-low latency networking
* **AWS Data Centers**
* **AWS Edge Locations / Points of Presence**
  * Amazon has 400+ Points of Presence (400+ Edge Locations & 10+ Regional Caches) in 90+ cities across 40+ countries
  * Content is delivered to end users with lower latency

## Shared Responsibility Model diagram
![Shared Responsibility Model diagram](https://github.com/hieunguyen-design/aws_ccp/blob/47d7da08015420e04ca219e6a54abf6b7a786d6a/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg)

## IAM: Users & Groups
* IAM  = Identity and Access Management, Global service
* Root account created by default, shouldn’t be used or shared
* Users are people within your organization, and can be grouped
* Groups only contain users, not other groups
* Users don’t have to belong to a group, and user can belong to multiple groups
