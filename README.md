# This is the repository where I will be talking about Solution Architecting and mostly will be discussing in Cloud and AWS. 


1) What is Cloud Computing
2) Different types of services provided by Cloud
3) Cloud Native Application development
4) Principles of SA design.
5) Could Migrations and Hybrid Architecture
6) SA design patterns

# What is Cloud Computing

Cloud computing is on-demand delivery of IT resources over internet with pay-as-you-go pricing.
users can the resources like compute, storage, network from a cloud provider and deploy the applications instead of buying new servers and setting up in a data center.

This brings agility to an idea as procuring, installing and setting up the hardware/software is time taking and incurs cost.

# Why we need cloud computing ?

 ## Lets take a real use case when a person gets an idea of starting a new business what exactly it happens where there is no cloud provider and what benifits the user will have with cloud computing

Situation : Let us say some one have an idea of starting a new online business like a small fashon store that sells trendy oufits to different customers.. 

## What is needed here ?

1) A website that has details about the outfit
2) A physical server that can hold the website
3) A database to store the inventory, customer details etc
4) A DNS server mapping the domain name to the machine IP address
5) Some other needed..


## What is done next when there is no cloud provider ?

The person who got the idea need to start working on below things irrespective of having the situation if the idea will really work or not.

1) Buy a new machine (could be computer, a server etc)
2) Hire a person who can help in desigining the website 
3) A place where to install the server, maintain the server like cooling, power, power-backup, HW maintenance etc.
4) Buy a domain name for publishing the server IP to a general name like www.newfashions.com
5) Some more activity that are needed.

## What is needed here ?

The person needs investment which is money i.e first CAPEX captial expense and let us assume it is approximately $ 1000 for buying the servers, creating the website, power consumption etc..

## How much time it takes to launch the website ?

The time it takes to launch the website from the time the idea is ignited approximately takes 2 months considering with some good amount of cost involved by hiring people..

## What can happen when the website is launched i.e after 2 months the idea is ignited

1) The idea mighn't work as expected as it is outdated
2) There are already similar business that might have started couple of weeks back.
3) Other issues that arise might cause the business not to run as expected

## What is the impact ?

1)  All the investment made on the HW is wasted
2)  All the time made is wasted
3)  All the effort spent on building the website is wasted
4)  The person is stressed.

## How cloud computing can help ?

As said cloud computing is about utilizing the needed resources like compute, storage, network and many more other services over internet with pay-as-you-go model.

## What this really mean here ?

When a person has an idea then he can register in a cloud provider website like (AWS, Azure or GCP) which absolutely free of cost. Once the registration is done he/she can launch the needed resources for the website creation and utilize as needed. The person can pay only for the time utilized.

In this scenario the below happens.

1) Register in a cloud provider website
2) Login and explore the needed options required for building the website.
3) Launch virtual servers called VM's based on the needed capacity like CPU,memory, basic storage etc.
4) Create a virtual private network which is secured and no one can access the resources without explicit permissions being provided.
5) Can utilize the natively available DNS server and integrate

## How the user is benifited ?

The user can work on the idea by launching the servers, providing the needed network connectivity and don't bother about procuring the servers, space for installation, network connectivity, cooling, power supply etc.

This makes the life easy to only concentrate on the actual business and how to improve the customer experience and don't need to worry about all other stuff. The cloud provider will take care of the HW provisioning and maintaining.

## What this really means ?

1) Brings agility to the idea. Once the idea is ignited the same can be implemented in hours or couple of days.
2) No CAPEX needed and can only pay for the time the resources are utilized
3) No need to hire people for developing the website and setting up the things
4) No need to buy a Domain Name separately 
5) No need to buy the power backup equipments etc 

## What is the outcome ?

The user don't need to spend $ 1000 from his/her pocket instead can only spend $ 200 which will reduce the CAPEX by 70% and there is no OPEX at all.
The idea will be live in couple of days rather than taking months and can capture the market before others.
The person can experiment with different features by modifying existing resources or add more without any prior approvals and just by doing few clicks.

## What if the idea clicks and the business grows ?

If the idea clicks and the business is running as expected then the person starts getting some ROI (Retrun on Investment) and thinks on expanding the business. This means the user base increases and more traffic is expected to reach the website which the servers has to be scaled.

Cloud providers can help to provide the needed resources without any prior information and can launch as many resources as needed.
As well there are many other managed services being offered by the cloud providers which the users can concentrate on the business and don't need to bother about the HW, power,cooling, patching, network etc.


## What are the benifits of cloud computing

Agility :

<img width="149" alt="image" src="https://user-images.githubusercontent.com/31388628/169976196-0aa1d704-ea0a-40b6-abb1-2b492ef677cc.png">

Cloud gives the easy access to variety of services that any one can access and innovate faster and build what has been imagined.Any one can quickly spin-up resources from IaaS like compute, storage, netwkork to other managed services like database, IoT, ML etc.

Any one can deploy technology services with in matter minutes. Cloud gives the freedom to experiment, test new ideas and transform the business.

Elasticity :

<img width="102" alt="image" src="https://user-images.githubusercontent.com/31388628/169977742-9b2a4b74-5725-46e4-8f9b-9a67424fc49b.png">

With cloud there is no need to over-provision of resources upfront to handle peak levels of business activity for future. Users can scale on demand based on the growing business. There is also a flexibility to shrink the resources when not needed this gives the exact benifit of cost optimization.

Cost Savings :



The cloud allows to trade fixed expenses (such as data centers) to variable expenses and pay only for what has been utilized.With the economies of scale cloud provides the resources at lower cost compared to what one has to set by their own.


Deploy globally in minutes :

<img width="130" alt="image" src="https://user-images.githubusercontent.com/31388628/169979856-a995d0bd-f5c8-4129-933d-1e2aa5fa5a98.png">


With cloud the business can expand to new geographies and can be deployed in minutes.General any cloud provider will have data centers i.e provide the infrastructure services across the world and users can deploy the needed resources for their business to serve near to the customers locations within minutes or hours.

