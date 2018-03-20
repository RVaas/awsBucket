---
layout: page
title: 
permalink: /overview/services/
---

Compute
=======

|EC2|Virtual Machines inside AWS, Dedicated VMs and Remote Access VMs are available|
|ECS|EC2 Container Services, Allows Docker Container execution|
|Elastic Beanstalk|For developers who don't understand AWS; just upload the code and Beanstalk will provision auto-scaling groups, EC2 instances, VPC, etc|
|Lambda|Used when code is uploaded to cloud and set up for event based triggers without worrying about the underlying platform/ VMs|
|Lightsail|Amazon's VPS service, designed for customers who care less about the underlying AWS infrastructure. Provisions you with a fixed IP, RDP access for Windows & SSH for Linux|
|Batch|Batch services for AWS|

Storage
=======

|S3|Simple storage service, **Object based** storage, stores objects in *Buckets* over the cloud|
|EFS|Elastic File System, Network attached storage, best for storing files and attach to multiple VMs|
|Glacier|For data archival, cheapest storage|
|Snowball|Used for transferring large volumes of data to AWS; physical device will be shipped by AWS to copy data & will be picked up for transfer to target VMs|
|Storage Gateway|Virtual appliances, VMs that we install on Data center of head office and will replicate information to S3|

Databases
=========

|RDS|Relational database service, supports SQL Server, MySQL, Oracle, Postgre SQL, Aurora|
|DynamoDB|Non-relational database, fully managed service by Amazon|
|Elasticache|Way of caching commonly queried data, reduces load on database|
|Red Shift|used for Data warehousing and Business Intelligence|

Migration
=========

|AWS Migration Hub|Tracking service for Migration|
|Application Discovery service|Tracks applications and dependencies|
|Database Migration service|For migration of DBs from on-premise to AWS|
|Server Migration service|Migration of virtual and physical servers to AWS|
|Snowball|Used for transferring large volumes of data to AWS; physical device will be shipped by AWS to copy data & will be picked up for transfer to target VMs|

Network and Content Delivery
============================

|VPC|*Virtual private cloud*, virtual data center in simple terms, for configuring firewalls, subnets, route tables, CIDR addresses, etc|
|Cloud Front| AWS Content delivery network, reduces latency using Edge Locations|
|Route 53|Amazon's DNS service|
|API Gateway|Creating own API's for services to talk|
|Direct Connect|Dedicated line from head office/ data center to Amazon VPC|
