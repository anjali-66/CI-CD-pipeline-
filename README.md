# CI-CD-pipeline-


Overview
This project sets up a Continuous Integration/Continuous Deployment (CI/CD) pipeline using AWS CodePipeline, CodeBuild, and CodeDeploy. The pipeline automates the build, test, and deployment of applications from a GitHub repository.
Pipeline Components
Source Control: GitHub repository
Continuous Integration: AWS CodeBuild
Continuous Deployment: AWS CodeDeploy
Pipeline Steps
Source: Pulls code changes from the dev branch in the GitHub repository
Build: Runs a build process using AWS CodeBuild, executing the steps defined in the buildspec.yml file
Deploy: Deploys the built application to a production environment using AWS CodeDeploy
Setup and Configuration
Create a GitHub repository and initialize a new repository or connect an existing one
Set up an AWS CodePipeline, CodeBuild, and CodeDeploy
Configure the pipeline to trigger on changes to the dev branch
Define the build steps in the buildspec.yml file
Configure the deployment settings in CodeDeploy
Usage
Make changes to the dev branch in the GitHub repository
Verify that the pipeline triggers and runs successfully
