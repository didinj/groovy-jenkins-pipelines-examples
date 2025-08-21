# Jenkins Groovy Pipeline Tutorial

Read the full tutorial [here](https://www.djamware.com/post/68a685c5379994426da054e7/using-groovy-for-jenkins-pipelines-a-practical-guide).

This project contains example Jenkins pipelines using Groovy:

- Declarative pipelines
- Scripted pipelines
- Dynamic and parallel execution
- Shared libraries for reusable code
- External configuration with JSON

## How to Use

1. Install Jenkins with the Pipeline plugin.
2. Create a new Pipeline job.
3. Point it to one of the Jenkinsfiles in this repo.
4. Configure a Shared Library in Jenkins:
   - Name: `my-shared-lib`
   - Repo: this repo
   - Path: `shared-library`
5. Run the pipelines 🚀
