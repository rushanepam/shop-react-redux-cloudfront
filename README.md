# React-shop-cloudfront

This is frontend starter project for nodejs-aws mentoring program.

- [CloudFront](https://d1sn14uqxbxjuk.cloudfront.net) link
- [S3Website](https://rushan-react-shop.s3.eu-west-1.amazonaws.com/index.html) is not available after applying a CloudFront related policy to it



Steps to deploy from the scratch:

- Delete all manually created resources(s3 buckets, CloudFront distributions, CloudFormation stacks)
- run cloudfront:setup
- run client:build:deploy
- run cloudfront:invalidateCache
