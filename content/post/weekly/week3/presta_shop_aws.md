---
title: Deploying PrestaShop on AWS with Micro-Service Architecture
summary:
date: Feb 23, 2022
author: admin
tags: ["Cloud", "Microservice", "Deployment", "DevOps"]
subtitle:
featured: true
categories: ["Cloud", "Microservice", "Deployment", "DevOps"]
draft: false
reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: true  # Show author profile?
commentable: true  # Allow visitors to comment? Supported by the Page, Post, and Docs content types.
editable: false  # Allow visitors to edit the page? Supported by the Page, Post, and Docs content types.
# header:
# image: "header.png"
# caption: "Image credit: [**Pexels.com**](https://www.pexels.com/photo/close-up-photo-of-cookies-3095041/)"
image:
  placement: 1
  caption: "PrestaShop"
  focal_point: "Center"
  preview_only: false
  alt_text: 
---
**Tools**

1. AWS EC2 instance (t2.micro)
2. Amazon RDS instance (Mysql) 
3. AWS cloudshell for CLI

**Steps**

1. Create and launch AWS EC2 instance from AWS console.
2. login to EC2 with ssh key and configure webserver on instance directly from AWS cloudshell
3. Setup Amazon RDS (mysql) as persistent datastore (database) for Prestashop
4. Install Prestashop  on Ec2 instance from cloudshell
5. Configure Prestashop from browser





To deploy the Prestashop software, i start by accessing the AWS console, I search for the EC2 service. I then proceed to create a new instance.

Here i am prompted to select a Amazon machine image or AMI, this is basically the OS that will run on the deployed instance created. I go for the Ubuntu Server version 20.04 as it is the latest version of the ubuntu OS image available. My thought is that the 64-bit(x86) option has greater popularity so i select that.
