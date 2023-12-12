## App Name
Sonarqube integration with AWS Code Pipeline + Github

## Objective
To perform a sonar scan and integrate the result in Sonarcloud with AWS code pipeline and Github.

## Pre-requisite(s)
1. We must have the AWS account with necessary permission.
2. Add/Manage the requires secrets with AWS "Secret Manager" service. In this project Used secret variables are: `sonartoken`, `HOST`, `Organization`, and `Project`
4. AWS Codebuild needs to be setup. While setting this up, we need to authenticate with Github so that it can read the source code
5. AWS Codepipeline needs to be setup.

## Steps to execute
1. Login to AWS Console.
2. Search for "Code Build".
3. Start the code build.
