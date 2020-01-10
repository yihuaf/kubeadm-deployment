A sample 2 node kube cluster using vagrant + kubeadm.

# To form the cluster

* deploy flannel network:`kubectl apply -f https://raw.githubusercontent.com/coreos/flannel/2140ac876ef134e0ed5af15c65e414cf26827915/Documentation/kube-flannel.yml`
* get the join command:
`kubeadm token create --print-join-command`

* for each node, run the output command with sudo.