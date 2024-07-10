### Kenta Goto (k.goto)

AWS DevTools Hero / AWS CDK Top Contributor & Trusted Reviewer / OSS developer of self-made AWS tools & CDK Construct libraries

<p align="left"> 
  <img alt="AWS CDK Contributor" height="150px" src="https://cdk-stats.vercel.app/api?username=go-to-k" />
  <img alt="Top Langs" height="150px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=go-to-k&layout=compact&show_icons=true" />
</p>

# My Tools

## CLI Tools

### [cls3](https://github.com/go-to-k/cls3)

The CLI tool to CLear S3 Buckets. It empties (so deletes all objects and versions/delete-markers in) S3 Buckets or deletes the buckets themselves.

### [delstack](https://github.com/go-to-k/delstack)

The CLI tool to force delete the entire AWS CloudFormation stack, even if it contains resources that fail to delete by the CloudFormation delete operation.

### [lamver](https://github.com/go-to-k/lamver)

The CLI tool to search AWS Lambda runtime and versions across regions.

## AWS CDK Construct Libraries

### [image-scanner-with-trivy](https://github.com/go-to-k/image-scanner-with-trivy)

The AWS CDK Construct library to allow you to scan a container image during CDK deployment layer with Trivy.

### [image-scanner-with-dockle](https://github.com/go-to-k/image-scanner-with-dockle)

The AWS CDK Construct library to allow you to scan a container image during CDK deployment layer with Dockle.

### [elb-other-5xx-alarm](https://github.com/go-to-k/elb-other-5xx-alarm)

The AWS CDK construct library for a CloudWatch Alarm for Elastic Load Balancing (as Application Load Balancer) that fires on HTTPCode_ELB_5XX_Count excluding 500, 502, 503, and 504 (e.g. 501, 505, 561).
