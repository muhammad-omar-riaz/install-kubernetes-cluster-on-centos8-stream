# install-kubernetes-cluster-on-centos8-stream
This configuration script could be used to deploy k8s cluster on 1 master node and 2 worker nodes.

# K8s Installation on Master Node 
Step-1: First run master-node.sh on master node
Step-2: You will get a command which you have to run on other (worker) nodes latter. You can find that command at any time in kubeadm-init.log which will be created during installation on master node.

# K8s Installation on Worker Node 1 
Step-3: Run worker-node1.sh on worker node 1. 
Step-4: You will have to enter cluster joining command which you will get in step-2.
Step-5: You have to label the worker node. For that enter command on master node. Command will be provided after installing k8s on worker node in step-3.

# K8s Installation on Worker Node 2
Step-6: Run worker-node2.sh on worker node 2. 
Step-7: You will have to enter cluster joining command which you will get in step-2.
Step-8: You have to label the worker node. For that enter command on master node. Command will be provided after installing k8s on worker node in step-6.
