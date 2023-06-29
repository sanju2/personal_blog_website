# personal_blog_website
Personal Blog Website Hosted on AWS

![Diagram](Architectural%20Diagram.png)

[Personal Website Link](https://devopswithlasantha.tech).

[Blog Post Link](https://dev.to/aws-builders/how-i-built-my-personal-blog-site-using-aws-services-51l7).

### Used to follow the steps.

 - Step 1 : Build my blog site in HTML with CSS.

- Step 2 : Created an S3 bucket to store portfolio files.

- Step 3 : Create Route53 Hosted zone and add copy NS records. Next, paste the ns record domain provider nameservers section.

- Step 4 : Next, go to the S3 bucket and enable Static website hosting, and map the Index document and Error document.

- Step 5 : Requested a public certificate for your domain in AWS Certificate Manager(ACM).

- Step 6 : Setup a CloudFront Distribution. Select S3 Static website hosting bucket endpoint and ACM public certificate.

- Step 7 : Next, create a Lambda function for the Visitor Count display. Used Python 3.9 runtime.

- Step 8 : Created DynamoDB table for Visitor count.

- Step 9 : Created APIGateway REST API and Invoke Lambda function.

- Step 10 : Create a git repository and push code.

- Step 11 : Create GitHub Actions for deploying S3 static website files and Lambda function codes.

- Step 12 : Finally, Push the latest release to Github.

### Thank You! :shipit: