Generate a static site using the Astro JS framework and deploy it to AWS. It will be hosted in an S3 bucket and served by CloudFront. You can use the CloudFormation template I’ve prepared to create the AWS infrastructure. You will update your website in your code editor, push it to GitHub where GitHub Actions will finish the deployment to AWS. Afterwards, use Route 53 for the domain name and ACM to generate an SSL certificate.

Full article here: https://ryanf.dev/posts/deploy-an-astro-site-with-s3-cloudfront-and-github-actions
