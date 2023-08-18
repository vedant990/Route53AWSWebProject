# My AWS Static Website Project

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

Welcome to the documentation for **My AWS Static Website Project**. This documentation provides a detailed overview of the project's purpose, setup, deployment, and usage.

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

Project Overview

Welcome to my AWS Static Website Project showcase! This project is a demonstration of how to create and deploy a static website using Amazon Web Services (AWS). By utilizing AWS Route 53 for domain management and Amazon EC2 for hosting the website content, this project showcases the seamless integration of AWS services for web hosting. Whether you're a newcomer to AWS or an enthusiast looking for a straightforward static website deployment, this showcase will walk you through the process step by step.

Prerequisites

Before diving into this showcase, make sure you have the following prerequisites:

    AWS Account: To begin, you'll need access to an AWS account in order to set up and manage the required resources.
    Basic AWS Knowledge: While no advanced knowledge is needed, a basic understanding of AWS services such as EC2 and Route 53 will be helpful.
    Registered Domain: You should have a registered domain name on AWS Route 53 that you'd like to associate with your static website.
    Git Installed: Git is a version control system that you'll use to clone the project repository and manage any code changes.

1. Create an EC2 Instance

Welcome to the "Create an EC2 Instance" section of my AWS Static Website Project showcase! In this section, we'll walk through the steps to set up an Amazon EC2 instance that will host your static website content.

To proceed, navigate to the Create an EC2 Instance guide.
2. Allocate an Elastic IP

In the "Allocate an Elastic IP" section, we'll ensure your website has a stable IP address by allocating an Elastic IP to your EC2 instance. This step is optional but highly recommended.

To continue, visit the Allocate an Elastic IP guide.
3. Create a Route 53 Hosted Zone

The "Create a Route 53 Hosted Zone" section will guide you through setting up a Route 53 hosted zone, allowing you to manage your domain's DNS records efficiently.

Jump to the Create a Route 53 Hosted Zone guide.
4. Create Record Sets

In this section, "Create Record Sets," we'll configure "A" or "AAAA" record sets in your Route 53 hosted zone to point to your EC2 instance. This step is crucial for connecting your domain to your website.

To proceed, follow the Create Record Sets guide.
5. Update DNS at Your Domain Registrar

In the "Update DNS at Your Domain Registrar" section, we'll walk you through the process of updating DNS records at your domain registrar to use Route 53 name servers. This step ensures proper routing of requests to your website.

For detailed instructions, head over to the Update DNS at Your Domain Registrar guide.
6. Upload Website Content

Now that your infrastructure is set up, it's time to upload your actual website content. In the "Upload Website Content" section, we'll guide you through connecting to your EC2 instance and uploading your HTML, CSS, and other assets.

To proceed, follow the Upload Website Content guide.
7. Access Your Website

Congratulations! In the "Access Your Website" section, we'll cover the final steps to access your static website using the domain you've set up. Your hard work will pay off as you see your website live on the internet.

To see your website in action, visit the Access Your Website guide.
## Contributing

We welcome contributions to improve and expand this project. Here's how you can contribute:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Make your changes and commit: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
