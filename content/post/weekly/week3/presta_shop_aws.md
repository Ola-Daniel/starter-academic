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
2. Amazon RDS instance for database based on mysql (db.t2.micro) 
3. AWS cloudshell for CLI

**Steps**

1. Create and launch AWS EC2 instance from AWS console.
2. login to EC2 with ssh key and configure webserver on instance directly from AWS cloudshell
3. Setup Amazon RDS (mysql) as persistent datastore (database) for Prestashop
4. Install Prestashop  on Ec2 instance from cloudshell
