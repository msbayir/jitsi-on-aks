Jitsi Setup on Azure Kubernetes Service

1. kubectl create namespace jitsi

2. deploy nginx ingress controller

3. Create rule for Azure Kubernetes Load Balancer UDP/30300. This will allow Load Balancer will be able to listen to request that are targeted 30300 port and route them to the proper machine. 

4. Create inbound security rule for 30300/UDP on VMSS Network Security Group 

