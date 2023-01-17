# k8s-onpremise-iac

kubeadm init --control-plane-endpoint="192.168.0.90:6443" --upload-certs --apiserver-advertise-address=192.168.0.81 --pod-network-cidr=10.79.0.0/16

kubectl create -f https://docs.projectcalico.org/manifests/calico.yaml

