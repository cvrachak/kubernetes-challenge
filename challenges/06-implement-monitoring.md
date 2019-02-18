# Implement A Monitoring Solution For Your Application

With a functional pipeline that builds and deploys your APIs, your next step is to focus on the health and performance of your APIs. Your challenge is to define and implement a monitoring strategy for your APIs.

## Challenge

In this challenge, carefully select the monitoring tool(s) that you want to use to achieve this challenge.

You are expected to achieve the following goals:

- Implement a solution that monitors the health and performance of your APIs. You will have to collect data regarding the performance of the cluster and the APIs.
- Define the performance baseline for the APIs running on your cluster and implement a mechanism that will automatically raise an alert and create an incident in your work item tracking system if a performance degradation is observed.
- Build a dashboard that will allow you to visualize the global health of your environment.

Using Azure Monitor For Containers or Promethus for this challenge will be the easiest, but feel free to choose a monitoring tool of choice.

## Success Criteria

Show to your coach the aggregated view of your application and infrastructure that includes the following:

- Cluster monitoring that display the CPU Usage of each node.
- The average response time over a period of 10 seconds for the 2 of the 4 microservices (Note Trips API you can monitor a single operation of the API).
NEED TO ADD MORE Here //TODO

#### Next Challenge: [Implement Rollout and Rollback Strategy](./07-implement-roll-out.md)

## References

[Setup Azure Container Insights For AKS](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-onboard)

[Setup Prometheus Operator](https://github.com/coreos/prometheus-operator)
