
# Home task

# Visual Studio Code Tips


cmd -shift -p preview markdown


## commands

```cd <folder name>```

Tasks:

1. [] Create VERY simple personal website (i.e your CV, could be just a few lines of text) - your test App. Could be even static html+css hosted on AWS CloudFront + S3, or some primitive JS, .Net or Python. Do no spend too much time on that, we just need some unique code to build, test and deploy.

2. Place source code in GIT (Github/Gitlab/AWS CodeCommit/...whatever_git)

3. Run it on AWS or GCP using Infrastructure as a Code approach (Terraform/AWS CloudFormation/AnyOtherSimilarTool). All the cloud infra definition to be in code in GIT near to your test App

4. Build a pipeline(any tool, could be part of GIT service provider toolset) with the following idea: when code of test App changed in GIT, run the simplest test (i.e some unit test or lint or any other), and deploy it to cloud, so it will be automatically updated for page visitors.

5. Connect it to any real DNS name, so visitors could find a few lines about you on the Internet in a convenient manner

6. Create a simple documentation about the project (readme file in GIT) and share GIT project incl readme by 16/01 end of the day for our evaluation

7. Prepare 10 min pitch showing how it works and explain why you choose your particular toolset.



Optional items:

1. Solution monitoring tools - ensure it is up and running with alerts if something goes wrong

2. Logging basic system log & alerts to have some traceability during solution operation (key actions to be logged, logs could be posted in the same way as alerts)