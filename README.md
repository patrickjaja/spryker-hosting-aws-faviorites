# Spryker PaaS Hosting Services

This document provides an overview of the AWS services used in a Spryker project, relevant for hosting. Each service is essential for different aspects of the Spryker PaaS Hosting concept.

| Icon                                                                                                                                 | Service              | Description                                                                                                                                             | Link                                                                                                                                                                                                                             |
|--------------------------------------------------------------------------------------------------------------------------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![CodeDeploy](https://d1idiovbex4hy4.cloudfront.net/icon/dc0ee5098cd676b9e0ff0ef4efe08836-ba08f633d12059af0acd90ac4404af86.svg)      | CodeDeploy           | Automates code deployments to any instance, including Amazon EC2 instances and instances running on-premises.                                           | [CodeDeploy](https://eu-central-1.console.aws.amazon.com/codesuite/codedeploy/deployments?region=eu-central-1&deployments-meta=eyJmIjp7InRleHQiOiIifSwicyI6e30sIm4iOjUwLCJpIjowfQ)                                               |
| ![S3](https://d1idiovbex4hy4.cloudfront.net/icon/c0828e0381730befd1f7a025057c74fb-43acc0496e64afba82dbc9ab774dc622.svg)              | S3                   | Scalable storage in the cloud.                                                                                                                          | [S3](https://eu-central-1.console.aws.amazon.com/s3/home?region=eu-central-1#)                                                                                                                                                   |
| ![CodeBuild](https://d1idiovbex4hy4.cloudfront.net/icon/13ee531096ccb4384d55f6b7cc66572b-9f8463d77a472721923c47b01f973d59.svg)       | CodeBuild            | Compiles source code, runs tests, and produces software packages that are ready to deploy.                                                              | [CodeBuild](https://eu-central-1.console.aws.amazon.com/codesuite/codebuild/home?region=eu-central-1#)                                                                                                                           |
| ![CloudWatch](https://d1idiovbex4hy4.cloudfront.net/icon/8f57ebd825a828e205b2dde223ba17e4-6af63a22dc297f8041286760ee8cd2c9.svg)      | CloudWatch           | Monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers.                        | [CloudWatch](https://eu-central-1.console.aws.amazon.com/cloudwatch/home?region=eu-central-1#home:)                                                                                                                              |
| ![ElastiCache](https://d1idiovbex4hy4.cloudfront.net/icon/23141cdce797eeb2bd54bba0e4e0968a-0394201dd8bdedfed719d44ff6a4c69b.svg)     | ElastiCache          | Deploy, operate, and scale an in-memory cache in the cloud.                                                                                             | [ElastiCache](https://eu-central-1.console.aws.amazon.com/elasticache/home?region=eu-central-1#/)                                                                                                                                |
| ![RDS](https://d1idiovbex4hy4.cloudfront.net/icon/1d374ed2a6bcf601d7bfd4fc3dfd3b5d-c9f69416d978016b3191175f35e59226.svg)             | RDS                  | Set up, operate, and scale a relational database in the cloud.                                                                                          | [RDS](https://eu-central-1.console.aws.amazon.com/rds/home?region=eu-central-1#)                                                                                                                                                 |
| ![Amazon MQ](https://d1idiovbex4hy4.cloudfront.net/icon/fbb6dfa8b3977184f170cc09442110d6-d925e664173507ede09f372672e53578.svg)       | Amazon MQ            | Managed message broker service for Apache ActiveMQ and RabbitMQ.                                                                                        | [Amazon MQ](https://eu-central-1.console.aws.amazon.com/amazon-mq/home?region=eu-central-1#/)                                                                                                                                    |
| ![ECR](https://d1idiovbex4hy4.cloudfront.net/icon/de7db04805a33606a40b897578543648-c0174badf433f1e0148e43426ae8e43a.svg)             | ECR                  | Fully managed Docker container registry that makes it easy to store, manage, and deploy Docker container images.                                        | [ECR](https://eu-central-1.console.aws.amazon.com/ecr/private-registry/repositories?region=eu-central-1)                                                                                                                         |
| ![OpenSearch](https://d1idiovbex4hy4.cloudfront.net/icon/18897dcfce6a4e7ae63a3baeed443c48-7724698ecde95174b630cef10d8335c2.svg)      | OpenSearch           | Search, visualize, and analyze up to petabytes of text and unstructured data.                                                                           | [OpenSearch](https://eu-central-1.console.aws.amazon.com/aos/home?region=eu-central-1#opensearch/dashboard)                                                                                                                      |
| ![Systems Manager](https://d1idiovbex4hy4.cloudfront.net/icon/b5c87c140628d6200f5ffeae85895b67-eed4319c5eaa4b84741dd26adcad7c1a.svg) | Systems Manager      | Provides a unified user interface so you can view operational data from multiple AWS services and automate operational tasks across your AWS resources. | [Systems Manager](https://eu-central-1.console.aws.amazon.com/systems-manager/home?region=eu-central-1#)                                                                                                                         |
| ![SES](https://d1idiovbex4hy4.cloudfront.net/icon/f2b32bda85a5a4a613eb47fb01c57ce3-2b4a0b6e3c7d785e7e0d22f5d540dce9.svg)   | Simple Email Service | - Used to configure identities (sender emailaddress) - Can be set to Sandbox mode, only allows sending mails to configured email addresses              | [SES](https://eu-central-1.console.aws.amazon.com/ses/home?region=eu-central-1)                                                                                                                                                  |
| ![EC2](https://d1idiovbex4hy4.cloudfront.net/icon/d88319dfa5d204f019b4284149886c59-7d586ea82f792b61a8c87de60565133d.svg)                                                  | EC2                  | Provides scalable computing capacity in the Amazon Web Services (AWS) cloud.                                                                            | [EC2](https://eu-central-1.console.aws.amazon.com/ec2/home?region=eu-central-1#Home:)                                                                                                                                            |
| ![ECS](https://d1idiovbex4hy4.cloudfront.net/icon/2eb2930111864beeb409e946751215b1-3ecb316865dc77cffc9cd77eed455da2.svg)                                                  | ECS                  | Highly scalable, high-performance container orchestration service that supports Docker containers.                                                      | [ECS](https://eu-central-1.console.aws.amazon.com/ecs/v2/clusters?region=eu-central-1)                                                                                                                                           |
| ![CodePipeline](https://d1idiovbex4hy4.cloudfront.net/icon/59874d8b5a9e702e16641126cc15e561-8137f94920dd8639de205d20e8e72ad6.svg)                                         | CodePipeline         | Continuous integration and continuous delivery service for fast and reliable application and infrastructure updates.                                    | [CodePipeline](https://eu-central-1.console.aws.amazon.com/codesuite/codepipeline/pipelines?region=eu-central-1&pipelines-meta=eyJmIjp7InRleHQiOiIifSwicyI6eyJwcm9wZXJ0eSI6InVwZGF0ZWQiLCJkaXJlY3Rpb24iOi0xfSwibiI6MzAsImkiOjB9) |
| ![SNS](https://d1idiovbex4hy4.cloudfront.net/icon/6002c6713f40e8a35d365605542e72b0-03c2386fb392e0d689e45d9b4f683a8d.svg)                                                  | SNS                  | Fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.                                | [SNS](https://eu-central-1.console.aws.amazon.com/sns/v3/home?region=eu-central-1#/homepage)                                                                                                                                     |
| ![Route 53](https://d1idiovbex4hy4.cloudfront.net/icon/f5d2c00d40914bff4f82f29f9ef768bc-53a84099cf556710383a52b4612a8612.svg)                                             | Route 53             | Scalable and highly available Domain Name System (DNS) web service.                                                                                     | [Route 53](https://us-east-1.console.aws.amazon.com/route53/v2/home?region=eu-central-1#Dashboard)                                                                                                                               |
| ![WAF](https://d1idiovbex4hy4.cloudfront.net/icon/47342d1bee153385294760bddb8a7f49-049868fe370f260d7efa3170efb113c3.svg)                                                  | WAF                  | Web application firewall that helps protect your web applications or APIs against common web exploits.                                                  | [WAF](https://us-east-1.console.aws.amazon.com/wafv2/homev2/home?region=eu-central-1#/)                                                                                                                                          |
