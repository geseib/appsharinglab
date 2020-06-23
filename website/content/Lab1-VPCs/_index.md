+++
title = "Lab 1: VPCs"
chapter = true
weight = 20
+++

## Lab 1 VPCs

This lab shows some of the basic networking aspects of **Amazon Virtual Private Cloud (VPC)**.

You will deploy two VPCs and the Transit Gateway with a few clicks using **AWS Cloudformation**. You will then connect to an EC2 instance and verify connectivity to the internet via the NAT Gateway, as well as test connectivity to the other VPCs EC2 instance.

![TGW Diagram](/images/tgw-diagram.png)

The address of the **EC2 Instance** in **VPC64** is **10.64.2.10** and the address of the **EC2 Instance** in **VPC65** is **10.65.2.10**.
