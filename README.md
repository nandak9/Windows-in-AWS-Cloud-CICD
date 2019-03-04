# quickstart-cicd-windows
## CI/CD Pipeline for Windows on the AWS Cloud

This Quick Start automatically deploys a continuous integration / continuous delivery (CI/CD) pipeline on AWS.

It uses standard Microsoft Windows technologies such as Microsoft Build Engine (MSBuild), Internet Information Services (IIS), Windows PowerShell, and .NET Framework in combination with the Jenkins CI tool and AWS services to deploy and demonstrate the CI/CD pipeline.

The AWS services for CI/CD include AWS CodePipeline, which is a CI orchestration service, and AWS CodeDeploy, which automates code deployments to Amazon Elastic Compute Cloud (Amazon EC2) instances.
You can use the Quick Start to integrate your own code push, build, and deploy pipeline with AWS services. You can also use the ASP.NET sample application provided with the Quick Start to see an automated end-to-end CI release deployed to AWS CodeDeploy servers that are running IIS.

![Quick Start CI/CD Pipeline for Windows Design Architecture](https://d3ulk6ur3a3ha.cloudfront.net/partner-network/QuickStart/datasheets/cicd-pipeline-for%20windows-on-aws-architecture.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the 
[deployment guide](https://fwd.aws/nrbbB).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.
If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
