# AWS Static Website Hosting

## Project Overview

This project demonstrates how to host a static website on AWS using Amazon S3 and Amazon CloudFront.

The project includes configuring website hosting, CloudFront distribution, custom domain (`vishvajeet.shop`), and secure HTTPS access.

**Live Website:** [https://vishvajeet.shop](https://vishvajeet.shop)

## AWS Services Used

- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- AWS Certificate Manager (ACM)

## Project Workflow

```
User (Browser)
     ↓
Custom Domain (vishvajeet.shop) via Route 53
     ↓
Amazon CloudFront (HTTPS + TLS Certificate)
     ↓
Amazon S3 (Static Website Files)
     ↓
Website Content
```

## What I Did

- Created an Amazon S3 bucket (`vishvajeet.shop`) in the Asia Pacific (Mumbai) region
- Uploaded static website files (HTML, CSS, JS, images) to S3
- Enabled bucket versioning
- Requested and validated a public SSL/TLS certificate using AWS Certificate Manager
- Created a CloudFront distribution with the S3 bucket as origin
- Configured custom domain name and HTTPS using the ACM certificate
- Created A and AAAA alias records in Route 53 pointing to CloudFront
- Tested the website over HTTPS

## Key Features

- Static website hosting on Amazon S3
- Global content delivery with Amazon CloudFront
- Custom domain configuration (`vishvajeet.shop`)
- Free SSL/TLS certificate via AWS Certificate Manager
- HTTPS-only secure access
- Highly available and scalable architecture

## Skills Demonstrated

- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- AWS Certificate Manager (ACM)
- DNS management
- HTTPS / SSL/TLS configuration
- Static Website Hosting
- AWS Cloud architecture

## Project Structure

```
aws-static-website-hosting/
├── README.md
├── project-files/
│   └── AWS_Static_Website.pdf          # Complete step-by-step documentation with screenshots
└── screenshots/
    ├── 1.png ... 11.png                # Console screenshots of the implementation
```

## Project Documentation

The complete project documentation with detailed implementation steps and screenshots is available here:

📄 **[View Project Documentation (PDF)](./project-files/AWS_Static_Website.pdf)**

## Project Status

✅ **Completed**

---

**Author:** Vishvajeet Shinde  
**Domain:** [vishvajeet.shop](https://vishvajeet.shop)
