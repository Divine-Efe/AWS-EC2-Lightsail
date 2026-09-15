# AWS EC2 & Lightsail — Week 1

Hands-on AWS practice covering EC2, Lightsail, Nginx, Node.js, networking, security groups, and AMI creation.

## Overview

This repository documents my hands-on AWS learning activities completed during Week 1.

The exercises covered launching and managing AWS resources, configuring web servers, deploying a simple application, working with security groups and Elastic IPs, and creating and testing Amazon Machine Images (AMIs).

## Technologies & Services

- Amazon EC2
- Amazon Lightsail
- Nginx
- Node.js
- WordPress
- AWS Security Groups
- Elastic IP
- Amazon Machine Images (AMI)
- Linux / Ubuntu
- GitHub

## Day 1 — EC2 Basics

- Launched an EC2 instance
- Configured SSH (port 22) and HTTP (port 80)
- Connected to the instance using SSH
- Installed and configured a web server
- Tested the web server through the instance's public IP

## Day 2 — EC2 Management & AMI

- Practiced stopping and starting an EC2 instance
- Created an Amazon Machine Image (AMI)
- Launched a new EC2 instance from the AMI
- Verified that the web server configuration was preserved

## Day 3 — Lightsail & WordPress

- Created an Amazon Lightsail instance
- Used the Linux/WordPress blueprint
- Connected using the Lightsail browser-based SSH
- Accessed the WordPress administrator dashboard
- Customized the WordPress site title

## Day 4 — Elastic IP & Security

- Allocated and associated an Elastic IP with the EC2 instance
- Accessed the web server using the Elastic IP
- Configured an inbound HTTPS (443) security-group rule
- Tested HTTPS connectivity

## Day 5 — Practical Tasks

### Task 1 — Nginx Web Server

- Configured an EC2 instance with Nginx
- Created a custom HTML page
- Hosted the page using Nginx
- Verified the page through the EC2 public IP

### Task 2 — Node.js Application

- Installed Node.js and npm on a Lightsail instance
- Created a simple Node.js HTTP application
- Configured port 3000
- Tested the application through the Lightsail public IP

### Task 3 — AMI Verification

- Created an AMI from the configured Nginx EC2 instance
- Launched a new EC2 instance from the AMI
- Verified that the Nginx configuration and custom web page were preserved

## What I Learned

- How to launch and manage EC2 instances
- How AWS security groups control inbound network traffic
- How to configure web servers on Linux
- How to deploy a simple Node.js application
- How Elastic IPs can provide a persistent public IP address
- How AMIs can be used to create new instances from an existing configuration
- How to document practical cloud projects using GitHub

## Documentation

Detailed evidence and screenshots for each day are available below:

- [Day 1 — EC2](./Day%201%20-%20Task.pdf)
- [Day 2 — EC2 & AMI](./Day%202%20-%20Task.pdf)
- [Day 3 — Lightsail & WordPress](./Day%203%20-%20Task.pdf)
- [Day 4 — Elastic IP & Security](./Day%204%20-%20Task.pdf)
- [Day 5 — Practical Tasks](./Day%205%20-%20Task.pdf)

## Note

This repository contains learning and practice work completed as part of an AWS hands-on worksheet.
