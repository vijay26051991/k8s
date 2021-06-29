#Kubernetes 

1. API server validates and configures the objects such replication, pod, deployment and replicaset etc.
    UI, API and CLI..

2. Controller manager.
      Node controller - Node goes down.
      Application controller - Ensure Minimum no of pod and replication running.
      Endpoint controller - How service communicate together.
      Service and token controller - create token for kubernetes.
  3. Scheduler - Pass information to worker nodes where application should be deployed.
  4. etcd - contains entire information about the kubernetes cluster.
  
  pods - smallest unit of deployable unit.
