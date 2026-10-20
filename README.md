# AWS S3 Static Website Hosting

## Project Overview

This project demonstrates how to deploy and host a static website using Amazon Simple Storage Service (Amazon S3).

The objective is to gain practical experience with AWS cloud storage, website hosting, access permissions, and basic cloud infrastructure configuration.

## AWS Services Used

- **Amazon S3** – Stores and hosts static website files.
- **AWS IAM / S3 Bucket Policy** – Controls access to AWS resources and website objects.

## Architecture

User → Internet → Amazon S3 Website Endpoint → HTML/CSS Files

## Implementation

1. Created an Amazon S3 bucket.
2. Developed a static website using HTML and CSS.
3. Uploaded website files to the S3 bucket.
4. Enabled static website hosting.
5. Configured a bucket policy to allow public read access.
6. Accessed and verified the deployed website using the S3 website endpoint.

## Security Considerations

The S3 bucket allows public read access to support static website hosting. No sensitive information is stored in the bucket.

The S3 website endpoint supports HTTP only. A future improvement would be to integrate Amazon CloudFront with HTTPS and restrict direct public access to S3.

## Project Outcome

Successfully deployed a functional static website using Amazon S3 and gained hands-on experience with AWS storage, resource permissions, and cloud-based website hosting.

## Future Improvements

- Integrate Amazon CloudFront for HTTPS delivery.
- Configure a custom domain using Amazon Route 53.
- Automate deployment using GitHub Actions.
- Implement monitoring and cost optimization.

## Lessons Learned

- Understanding how S3 static website hosting works.
- Configuring S3 bucket permissions and access policies.
- Troubleshooting website accessibility and file paths.
- Deploying a website using AWS cloud infrastructure.
