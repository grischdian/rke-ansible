# rke-ansible
THIS IS ONLY MADE FOR UBUNTU and LOCALHOST!
## Prerequests
Install ansbible and git
```
apt install ansible git
```
Clone this repository
```
git clone https://github.com/grischdian.de/rke-ansible.git
```

Run Ansible
```
cd rke-ansible
ansible-playbook kubernetes.yaml
```
Check Kubernetes
```
kubectl get nodes
```
