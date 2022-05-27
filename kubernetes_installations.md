Master Node instance 

sudo apt-get update
sudo apt-get install docker.io -y


sudo apt-get install apt-transport-https curl -y
wget https://packages.cloud.google.com/apt/doc/apt-key.gpg
sudo apt-key add apt-key.gpg

To disable swap temporary (as recommended):

sudo swapoff -a
To configure Kubernetes repository

sudo apt-add-repository "deb http://apt.kubernetes.io/ kubernetes-xenial main"
Install Kubeadm package:

sudo apt-get install kubeadm -y
Verification of kubeadm installation:

kubeadm version

sudo kubeadm init

Step 4: Set Up Kubeconfig
To set up the kubeconfig, I need to execute the below set of commands on the master as well as on the client machine.

mkdir -p $HOME/.kube
sudo cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
sudo chown $(id -u):$(id -g) $HOME/.kube/config

Worker Node Instance
Worker node install all same installation then execute add token command.
kubeadm join

kubectl get nodes
