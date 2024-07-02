# AspireDeploy

This sample .NET Aspire based project is paired with a blog post that demonstrates deploying to Azure for CI/CD using GitHub Actions. 

The blog post is available at [https://agramont.net/blog/devops-intro-deploy-net-aspire-azure-github-actions](https://agramont.net/blog/devops-intro-deploy-net-aspire-azure-github-actions).

The code itself is based on the [Quickstart: Build your first .NET Aspire project](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/build-your-first-aspire-app?pivots=visual-studio) 
tutorial.  

What is different is that the project has been modified to include a GitHub Actions workflow file that will build and deploy the project to Azure.  With special 
attention to spinning down and forcing a deployment when needed. 

For installation and setup instructions, please refer to the [blog post](https://agramont.net/blog/devops-intro-deploy-net-aspire-azure-github-actions).