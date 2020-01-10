A sample 2 node kube cluster using vagrant + kubeadm.

# To install dependencies
`sudo dnf install vagrant ansible`

# To form the cluster
`vagrant up`

# Other deployment
Use the ansible scripts under `./kubernetes-setup/`. Run master first, then node.