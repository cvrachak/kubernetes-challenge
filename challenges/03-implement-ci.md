# Implement Continous Integration (CI)

## Challenge
Select the tooling that best fits your team’s skills or learning plans, and implement the part of your pipeline that builds your application and pushes the container image to a registry. You are not expected to deploy any resources to the AKS cluster at this time in the challenge.

Create your own code repository either by forking the provided repo on Github or import into Azure Repos. Your pipeline should automatically make a link between a given build and its corresponding work items. You are expected to work on all the APIs of the application.

*NOTE:* If importing into Azure DevOps, be sure to set your project to public to increase your build agents from 1 to 10.

In Azure DevOps you can create the pipeline in YAML if you desire but we strongly recommend you start by using the visual designer.

If your team is planning to use Jenkins, using the public Helm Chart is the easiest way to get started. It will deploy a Jenkins Master and run the agents on your Kubernetes cluster.

You are expected to implement a policy so that any code change submitted must go through a peer review and formal approval process.

*NOTE:* Your team should be able to complete all challenges without needing to modify the API code. There is one exception where you may need to introduce a change to trigger an automated pipeline. Talk to your coach when you get to this step if you need help finding an easy change to make.

## References


## Jenkins Related Content

