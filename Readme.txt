Project: Deploy Static Website on AWS

Name: Shailendra Rai

Description:
This project demonstrates how to deploy a static website using Amazon S3 and distribute it globally using Amazon CloudFront.

Services Used:

* Amazon S3 (Static website hosting)
* AWS IAM (Bucket Policy)
* Amazon CloudFront (Content Delivery Network)

Steps Performed:

1. Created an S3 bucket and configured it for static website hosting.
2. Uploaded HTML, CSS, and JavaScript files.
3. Configured bucket policy to allow public read access.
4. Created a CloudFront distribution connected to the S3 bucket.
5. Configured the default root object as index.html.
6. Accessed the website using the CloudFront endpoint.

CloudFront Endpoint URL:
https://d1bjqkot7fhex0.cloudfront.net

S3 Website Endpoint:
http://shailendra-aws-static-website-2026.s3-website-ap-south-1.amazonaws.com

Notes:
CloudFront was used to improve performance and provide secure HTTPS delivery of the static website.
