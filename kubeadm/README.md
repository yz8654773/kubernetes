This is a document with a compiled kubeadm visa for 10 years.  
Download it and use it  
bash command： 
# ./Kubeadm-crt-10 alpha certs renew all --config={initialize the cluster's configuration file},  
The compilation parameter is the source location of a constant 1.16 version of the kubeadm module under the source code: kubernetes/cmd/kubeadm/app/constants.  
Content CertificateValidity = time.Hour * 24 * 3650
