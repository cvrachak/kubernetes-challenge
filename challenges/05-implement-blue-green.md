# Implement A Basic Blue/Green Deployment

In the previous challenges, your team has implemented a set of pipeline(s) that implements Continuous Integration and Continuous Deployment however your deployment mechanism may require downtime that can interfere with the functionality of the application and services that depend on it. Rollback is another consideration during deployment should the deployment encounter issues.

Blue/Green deployment strategy involves having two environments and shifting traffic from blue to green. Blue or green can be your vCurrent version with the other being vNext. An upgrade involves simply shifting traffic from one environment to the other and a rollback is the reverse of this process. In this challenge our environment will be the deployed microservice deployed via Helm for the service you intend to upgrade. Focus on the mechanics of upgrade/rollback via your pipeline.

You will now implement a Blue/Green deployment mechanism for your APIs that aims to eliminate downtime while allowing for ease of rollback. This is different from flighting or canary testing which is covered in a later challenge.

## Challenge

With the tooling that you have selected previously, your challenge is to update your pipeline to perform Blue/Green deployment automatically.

All changes to the chart are already available to your team and you only need to uncomment them. Refer to the links provided to get a better understanding of Blue/Green deployment with Kubernetes. We have selected Traefik to be the ingress controller for this environment, the logic that you will implement applies to other ingress controllers on Kubernetes.

It is recommended to think about your strategy as a team before you start coding.

From now downtime in the deployment does count against your score.

## Success Criteria

Explain to your coach the logic that you are using for blue/green deployment and address the following points:

- Describe the mechanism that validates that the container is ready?
- What are you using to perform the rollback to the previous version?
- How do you manage the version deployed?
- Demonstrate that a code change in your API is deployed initially to an environment and automatically switched to a new one with no downtime for this API.

Demonstrate a simple decision point to close out the release or rollback in your pipeline.

Demonstrate you can roll back to the previous version. Teams can rollback via pipeline automation or from cmd line issuing commands with Helm or Kubectl.

To successfully complete the challenge, it is expected to implement the strategy for at least one API. You coach will give you a change to push through your pipeline to test your strategy.

#### Next Challenge: [Implement Monitoring](./06-implement-monitoring.md)

## References

- Blue/Green Deployment
- Liveness and Readiness Probes In Kubernetes
- Kubernetes Max Unavaliable Strategy
- Helm Rollback