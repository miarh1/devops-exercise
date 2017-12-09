# Exercise
AWS Jenkins Deployment Pipeline
 
## Requirements
The candidate should set up a continuous build pipeline using Jenkins, Github and Amazon EC2 service. 

Some requirements are left intentionally vague:

 * There must be a hello world web application in your personal Github account. The language doesn't matter, e.g. ruby, python, java, etc.
 * There must be a running instance of Jenkins in AWS with a public DNS name 
 * There must be a running instance of your application in AWS with a public DNS name
 * Github must be configured to notify the Jenkins instance on every commit
 * Jenkins must be configured to build and deploy a Docker image on every commit notification from Github
 * Your application instance must reflect changes from every commit pushed to Github
 * Bonus points for use of configuration management and database

## Submission
Once the exercise is completed, the candidate must do the following:

 * Add 'zishan' as a collaborator to your hello world repository
 * Email the following to zahmad(at)teladoc.com
   * Github url for the hello world repository
   * Public DNS name for the Jenkins instance (and any relevant credentials for admin access)
   * Public DNS name for the application instance

## Evaluation
After the candidate has provided their submission:

 1. We will post a commit to the hello world repository and verify the pipeline works and all requirements are satisfied
 2. We will then schedule a phone call to discuss the implementation in detail. 

We want to see that the candidate can speak to implementation decisions and the reasoning behind them. Additionally, we're looking for familiarity with our chosen technology stack or the capacity to apply familiar concepts to unfamiliar technologies.
