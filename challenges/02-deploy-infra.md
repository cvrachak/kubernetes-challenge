# Build Your Platform
In this challenege you'll need to deploy a Kubernetes cluster with AKS, setup Helm, deploy a Ingress Controller of your choice, and deploy a MongoDB compatible database.

## Challenge

To complete future challenges you'll need to setup the following infrastructure for your application.

- 3 Node AKS Cluster
- Install Helm
- Setup Ingress Controller with Helm
- Create a CosmosDB(MongoDB API) or deploy MongoDB to your Kubernetes cluster.

## Success Criteria

Show to your coach that you have a fully functioning three node AKS cluster, working Ingress, and a MongoDB compliant database deployed.

You will need to document the MongoDB connection string to perform future challenges.

#### Next Challenge: [Implement Continous Integration](./03-implement-ci.md)

## References

[Create AKS Cluster](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)

[Install Helm On AKS](https://docs.microsoft.com/en-us/azure/aks/kubernetes-helm)

Setup Kubernetes Ingress Controller

- [Nginx](https://docs.microsoft.com/en-us/azure/aks/ingress-tls)
- [Ambassador](https://www.getambassador.io/user-guide/getting-started/)
- [Traefik](https://docs.traefik.io/user-guide/kubernetes/)

[Create CosmosDB With MongoDB API](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-introduction)

[Deploying MongoDB On Kubernetes](https://kubernetes.io/blog/2017/01/running-mongodb-on-kubernetes-with-statefulsets/)