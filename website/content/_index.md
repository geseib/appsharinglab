+++
title = "Application Sharing"
chapter = false
weight = 20
+++

## Application Sharing in Amazon Virtual Private Cloud (VPC)

### What to expect

This workshop shows some of the basic networking aspects of sharing a Load Balanced Application across VPCs.

Within your own AWS account, you can explore how to provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.

![End-to-end Apps](/images/r53-diagram.png)

You will use the following services:

- **AWS Network Load Balancers** for a scalable application
- **AWS Privatelink** and **Transit Gateway** for cross VPC communication
- **Amazon Route 53** for DNS and directing clients to the correct resource
