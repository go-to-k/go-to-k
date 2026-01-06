# Kenta Goto

- [AWS DevTools Hero](https://aws.amazon.com/jp/developer/community/heroes/kenta-goto/)
- [AWS CDK Top Contributor](https://github.com/aws/aws-cdk/blob/main/CONTRIBUTORS.md) & [Community Reviewer](https://github.com/aws/aws-cdk/wiki/CDK-Community-PR-Reviews#trusted-cdk-reviewers)
- Maintainer of the [Open Constructs Library](https://github.com/open-constructs/aws-cdk-library), a Community-Driven CDK Construct Library
- OSS creator of AWS tools & CDK Construct libraries

<p align="left"> 
  <img alt="AWS CDK Contributor" height="150px" src="https://cdk-stats.vercel.app/api?username=go-to-k" />
</p>

# Blog Posts (En/Ja) and Slides

- [English](https://dev.to/k_goto)
- [Japanese](https://go-to-k.hatenablog.com/)
- builders.flash (Official web magazine by AWS Japan)
  - [AWS CDK におけるバリデーションの使い分け方を学ぶ](https://aws.amazon.com/jp/builders-flash/202406/cdk-validation/)
  - [AWS CDK における単体テストの使い所を学ぶ](https://aws.amazon.com/jp/builders-flash/202411/learn-cdk-unit-test/)
  - [AWS CDK におけるプロパティ一括適用 TIPS 集](https://aws.amazon.com/jp/builders-flash/202601/cdk-property-bulk-apply/)
- [Slides](https://speakerdeck.com/gotok365)

# Self-developed OSS

## AWS Dev Tools

### [cls3](https://github.com/go-to-k/cls3)

The CLI tool to CLear S3 Buckets. It empties (so deletes all objects and versions/delete-markers in) S3 Buckets or deletes the buckets themselves.

### [delstack](https://github.com/go-to-k/delstack)

The CLI tool to force delete the entire AWS CloudFormation stack, even if it contains resources that fail to delete by the CloudFormation delete operation.

### [lamver](https://github.com/go-to-k/lamver)

The CLI tool to search AWS Lambda runtime and versions across regions.

## AWS CDK Construct Libraries

### [image-scanner-with-trivy](https://github.com/go-to-k/image-scanner-with-trivy)

The AWS CDK Construct library to allow you to scan a container image during CDK deployment layer with Trivy.

To my surprise, this library was featured on the ecosystem page of [Trivy's official documentation](https://aquasecurity.github.io/trivy/latest/ecosystem/ide/#image-scanner-with-trivy-community)!

### [image-scanner-with-dockle](https://github.com/go-to-k/image-scanner-with-dockle)

The AWS CDK Construct library to allow you to scan a container image during CDK deployment layer with Dockle.

### [elb-other-5xx-alarm](https://github.com/go-to-k/elb-other-5xx-alarm)

The AWS CDK construct library for a CloudWatch Alarm for Elastic Load Balancing (as Application Load Balancer) that fires on HTTPCode_ELB_5XX_Count excluding 500, 502, 503, and 504 (e.g. 501, 505, 561).
