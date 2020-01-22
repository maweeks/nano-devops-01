# Udacity Cloud Dev Ops Engineer Nanodegree Project 01

Deploy a static website to AWS using S3, IAM and CloudFront.

## CloudFront endpoint

[d2yd3iqe1xnz2m.cloudfront.net](d2yd3iqe1xnz2m.cloudfront.net)

## Steps / Proof

S3 Bucket created

![S3 Bucket created screen shot](./img/01-createBucket.png "S3 Bucket created screen shot")

Files uploaded to S3 bucket

![Files uploaded to S3 bucket screen shot](./img/02-uploadFiles.png "Files uploaded to S3 bucket screen shot")

S3 bucket set to support static web hosting

![S3 bucket set to support static web hosting screen shot](./img/03-staticWebHosting.png "S3 bucket set to support static web hosting screen shot")

S3 bucket is publicly accessible

![S3 bucket is publicly accessible screen shot](./img/04-bucketPublic.png "S3 bucket is publicly accessible screen shot")

CloudFront configured to retrieve and distribute website files

![CloudFront configured to retrieve and distribute website files screen shot](./img/05-cloudFrontDistribution.png "CloudFront configured to retrieve and distribute website files screen shot")

Also, updated the default root object to `index.html` so that it automatically redirects to the website.

![CloudFront configured default root object screen shot](./img/06-defaultRootObject.png "CloudFront configured default root object screen shot")
