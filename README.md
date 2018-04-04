# quickstart-pivotal-cloudfoundry
## Pivotal Cloud Foundry (PCF) on the AWS Cloud


This Quick Start automatically deploys Pivotal Cloud Foundry (PCF) into your Amazon Web Services (AWS) account.

PCF is a cloud-native platform for deploying and operating modern applications. You can build your applications in Spring or .NET, and then deploy your code to the platform. PCF does the rest, handling much of the operational complexity for you. 

This Quick Start deploys the PCF architecture into a virtual private cloud (VPC) with two public and four private subnets in your AWS account. The deployment and configuration tasks are automated by AWS CloudFormation templates that you can customize during launch. The deployment guide provides architectural details and step-by-step deployment instructions.

The Quick Start offers two deployment options:

- Starter deployment, which deploys about 22 EC2 instances. You can scale the platform later to add more capacity after the initial deployment. 
- Multi-AZ deployment, which includes about 40 EC2 instances spanning two Availability Zones, for near production-grade use.

You can also use the AWS CloudFormation templates as a starting point for your own implementation.

![Quick Start architecture for PCF on AWS](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/pcf-on-aws-architecture-multi-az.png)

For architectural details, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/wbrj3).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.

We do not accept pull requests on this repo; please submit all changes to https://github.com/cf-platform-eng/aws-pcf-quickstart.
