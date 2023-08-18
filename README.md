# My AWS Static Website Project

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

Welcome to the documentation for **My AWS Static Website Project**. This documentation provides a detailed overview of the project's purpose, setup, deployment, and usage.
![image](https://github.com/vedant990/Route53AWSWebProject/assets/121371568/45ff2dcc-49e2-47f8-8845-f6e40311df82)

https://github.com/vedant990/Route53AWSWebProject/assets/121371568/65f8f89a-a182-4b03-8563-a8381a19abde



## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Setup Instructions](#setup-instructions)
    - [1. Create an EC2 Instance](#1-create-an-ec2-instance)
    - [2. Allocate an Elastic IP](#2-allocate-an-elastic-ip-optional-but-recommended)
    - [3. Create a Route 53 Hosted Zone](#3-create-a-route-53-hosted-zone)
    - [4. Create Record Sets](#4-create-record-sets)
    - [5. Update DNS at Your Domain Registrar](#5-update-dns-at-your-domain-registrar)
    - [6. Upload Website Content](#6-upload-website-content)
    - [7. Access Your Website](#7-access-your-website)
4. [Contributing](#contributing)
5. [License](#license)

# Project-overview

Welcome to my AWS Static Website Project showcase! This project is a demonstration of how to create and deploy a static website using Amazon Web Services (AWS). By utilizing AWS Route 53 for domain management and Amazon EC2 for hosting the website content, this project showcases the seamless integration of AWS services for web hosting. Whether you're a newcomer to AWS or an enthusiast looking for a straightforward static website deployment, this showcase will walk you through the process step by step.

# Prerequisites

Before diving into this showcase, make sure you have the following prerequisites:

    AWS Account: To begin, you'll need access to an AWS account in order to set up and manage the required resources.
    Basic AWS Knowledge: While no advanced knowledge is needed, a basic understanding of AWS services such as EC2 and Route 53 will be helpful.
    Registered Domain: You should have a registered domain name on AWS Route 53 that you'd like to associate with your static website.
    Git Installed: Git is a version control system that you'll use to clone the project repository and manage any code changes.

# Create an EC2 Instance

    Log in to your AWS Management Console.
    Navigate to the EC2 dashboard.
    Click on "Launch Instance" to create a new EC2 instance.
    Choose an appropriate Amazon Machine Image (AMI) based on your website's requirements.
    Configure instance details, including instance type, network settings, and storage.
    Configure security groups to allow incoming web traffic (HTTP/HTTPS).
    Create or select an existing key pair for SSH access to the instance.
    Review your configuration and launch the instance.

# Allocate an Elastic IP (Optional but Recommended)

Ensure a stable IP for your website with an Elastic IP:

    In the EC2 Dashboard, navigate to "Elastic IPs."
    Click on "Allocate new address" and then "Allocate."
    Select the newly allocated Elastic IP and choose "Actions" > "Associate IP address."
    Associate the Elastic IP with your EC2 instance.

To continue, visit the Allocate an Elastic IP guide.
# Create a Route 53 Hosted Zone

Manage your domain's DNS records using Route 53:

    In the Route 53 Dashboard, click "Create Hosted Zone."
    Enter your domain name (e.g., example.com) and create the hosted zone.

Jump to the Create a Route 53 Hosted Zone guide.
# Create Record Sets

IConnect your domain to your EC2 instance:

    Inside your hosted zone, click "Create Record Set."
    Create an "A" record or "AAAA" record (for IPv6) pointing to your EC2 instance's Elastic IP address.
To proceed, follow the Create Record Sets guide.
# Update DNS at Your Domain Registrar

Update DNS for proper routing:

    Go to your domain registrar's website and log in.
    Update the DNS records for your domain to use Route 53 name servers.
    Wait for DNS changes to propagate (may take some time).

For detailed instructions, head over to the Update DNS at Your Domain Registrar guide.
# Upload Website Content

Upload your website files to your EC2 instance:

    SSH into your EC2 instance using the key pair you configured during instance setup.
    Upload your website's HTML, CSS, and other assets to the appropriate directory on the instance.

To proceed, follow the Upload Website Content guide.
# 7 Acess Your Website

    Ensure that you have completed all the previous setup steps, including creating an EC2 instance, allocating an Elastic IP, setting up a Route 53 hosted zone, creating record sets, updating DNS at your domain registrar, and uploading your website content.

    Once the DNS changes have propagated (this may take some time), open a web browser.

    In the address bar, enter your registered domain name (e.g., http://www.example.com) and press Enter.

    Voila! Your static website should now be accessible, and you can explore it by navigating through its pages, links, and content.

## Contributing

We welcome contributions to improve and expand this project. Here's how you can contribute:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Make your changes and commit: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
