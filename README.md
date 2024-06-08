# aws-sample-cfn-ec2-alb-cf
EC2, ALB, CloudFrontをCloudFormationで立てるためのサンプルコードです。

## 前提
- VPC, Subnetはご自身でご用意の上、Parameterに記載ください。

## 実行順
1. ``ec2/template.yaml``
2. ``alb/template.yaml``
3. ``cloudfront/template.yaml``
の順でdeployしてください。