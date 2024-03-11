Stopping a cluster.
kubeadm reset -f --cri-socket=unix:///var/run/containerd/containerd.sock
rm -rf /etc/kubernetes /var/lib/kubernetes /var/lib/etcd
systemctl stop kubelet






