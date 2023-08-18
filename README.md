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

Setup Overview

This showcase will guide you through the process of deploying your static website using AWS services. Here's an overview of the steps you'll take:

    Create an EC2 Instance: Launch an Amazon EC2 instance to serve as the host for your static website.
    Allocate an Elastic IP (Optional but Recommended): Ensure a stable IP address for your website by allocating an Elastic IP.
    Create a Route 53 Hosted Zone: Set up a Route 53 hosted zone to manage your domain's DNS records.
    Create Record Sets: Configure "A" or "AAAA" record sets in Route 53 to point to your EC2 instance.
    Update DNS at Your Domain Registrar: Make changes at your domain registrar to use Route 53 name servers.
    Upload Website Content: Connect to your EC2 instance and upload your website's HTML, CSS, and other assets.
    Access Your Website: Once everything is set up, your static website will be accessible using your registered domain name.
...

### 7. Access Your Website

1. Wait for DNS propagation to complete.
2. Open a web browser and enter your domain name (e.g., http://www.example.com) to access your static website.

## Contributing

We welcome contributions to improve and expand this project. Here's how you can contribute:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Make your changes and commit: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
