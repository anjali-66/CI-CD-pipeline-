# CI-CD-pipeline-


Overview
This project sets up a Continuous Integration/Continuous Deployment (CI/CD) pipeline using AWS CodePipeline, CodeBuild, and CodeDeploy. The pipeline automates the build, test, and deployment of applications from a GitHub repository.


Pipeline Components

1.Source Control: GitHub repository
2.Continuous Integration: AWS CodeBuild
3.Continuous Deployment: AWS CodeDeploy


Pipeline Steps

1.Source: Pulls code changes from the dev branch in the GitHub repository
2.Build: Runs a build process using AWS CodeBuild, executing the steps defined in the buildspec.yml file
3.Deploy: Deploys the built application to a production environment using AWS CodeDeploy.


Setup and Configuration

1.Create a GitHub repository and initialize a new repository or connect an existing one
2.Set up an AWS CodePipeline, CodeBuild, and CodeDeploy
3.Configure the pipeline to trigger on changes to the dev branch
4.Define the build steps in the buildspec.yml file
5.Configure the deployment settings in CodeDeploy



Usage
1.Make changes to the dev branch in the GitHub repository
2.Verify that the pipeline triggers and runs successfully
3.Check the deployment status in CodeDeploy


Files and Directories

1.buildspec.yml: defines the build steps for AWS CodeBuild
2. .gitignore: ignores files and directories not needed in the pipeline
