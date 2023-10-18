# K8sExpert

### Instalando Kind

```
curl -Lo ./kind <https://kind.sigs.k8s.io/dl/v0.20.0/kind-linux-amd64>

chmod +x ./kind
sudo mv ./kind /usr/local/bin/kind
```

### Instalando kubectl  Ubuntu 18.04


```
curl -s <https://packages.cloud.google.com/apt/doc/apt-key.gpg> | sudo apt-key add
apt install curl

apt-add-repository "deb <http://apt.kubernetes.io/> kubernetes-xenial main"

apt install kubeadm kubelet kubectl

apt-mark hold kubeadm kubelet kubectl

kubeadm version
```

By Marcio Felder.
