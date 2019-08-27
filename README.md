﻿# Deploy Static Website on AWS

> This project demonstrates how to deploy a static website to AWS.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/320px-Amazon_Web_Services_Logo.svg.png)

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)

The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. This project demonstrates how to deploy a static website to AWS. The first step is to create a S3 bucket and upload the website files to your bucket. Next is to configure the bucket for website hosting and secure it using IAM policies. Afterwards, to speed up content delivery using AWS’ content distribution network service, CloudFront is used. Lastly, the website can then be accessed in a browser using the unique CloudFront endpoint.

## Website Files Criteria

### The S3 bucket is visible in the AWS Management console.
![Screenshot](1-s3-bucket-created.png) 

### All website files should be added to the S3 bucket.
![Screenshot](2-website-files-uploaded-to-s3-bucket.png) 

### The bucket configuration should be set up to support static website hosting.
![Screenshot](3-s3-bucket-configured-to-support-static-website-hosting.png) 

### The permission access to the bucket should be configured to allow public access.
![Screenshot](4-s3-bucket-IAM-policy-created.png) 

## Website Distribution Criteria

### The website should be distributed via Cloudfront.
![Screenshot](5-cloudfront-configured-to-retrieve-and-distribute-website-files.png) 

## Web Browser Access Criteria

### Is the website publicly accessible?
![Screenshot](6-website-publicly-accessible.png) 

* **Website URL:** http://d3asysg8crldu.cloudfront.net/index.html

## Built With

* [Amazon Web Services S3](https://aws.amazon.com/s3/) - Resource hosting and deployments
* [AWS CloudFront](https://aws.amazon.com/cloudfront/) - CDN for SPA

## Authors

* **[Pemberai Sweto](https://github.com/thepembeweb)** - *Initial work* - [Item Catalog](https://github.com/thepembeweb/aws-static-website-deployment)

## License

[![License](http://img.shields.io/:license-mit-green.svg?style=flat-square)](http://badges.mit-license.org)

- This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
- Copyright 2019 © [Pemberai Sweto](https://github.com/thepembeweb).
