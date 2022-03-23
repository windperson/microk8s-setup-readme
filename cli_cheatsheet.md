# MicroK8s useful commands

* Start MicroK8s VM instance and Kubernates cluster:
   ```
   microk8s start
   ```
* Stop MicroK8s Kubernates cluster and its VM instance:
   ```
   microk8s stop
   ```
* Check current MicroK8s service status & list activated add-on services:
   ```
   microk8s status --wait-ready
   ```
* SSH into microk8s Linux VM:
   ```
   multipass shell microk8s-vm
   ```
* List all running pods/services/deployments:
   ```
   microk8s kubectl get all -A 
   ```
