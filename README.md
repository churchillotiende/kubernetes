# Making kubectl command executable
`chmod +x ./kubectl`

# Move the binary to your local path
`sudo mv ./kubectl /usr/local/bin/kubectl`

## Checking whether virtualisation is enabled for mac machine
`sysctl kern.hv_support
`

## What is docker
`virtualisation software,makes developing and deploying applications much easier`
`Packages applications will all the necessary dependencies,configuration,system tools and runtime`
`Portable artifact, easily shared and distributed`
## Minikube Update Context
`Run the following command to refresh local environment and force kubectl to update its port mappings`
`minikube update-context`
# kubernetes

## Removing an already committed file to its
`git rm --cached <file_name>`

## Deleting a pod using kubectl
`kubectl delete pod <pod name>`

## Kubeernetes controllers
### Replication controllers
`Helps us to run multiple instances of a single pod thus providing high availability`
`Load balancing and scaling`

`kubectl create -f rc-defintion.yaml`
`kubectl  get replicationController`

## Pods created by the replication controllers
`kubectl get pods`
