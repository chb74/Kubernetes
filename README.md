# Kubernetes 가이드 

# -- Dec 5, 2021 

```console 
docker pull smlinux/nodeinfo:v1
docker create --name app -p 80:8080 smlinux/nodeinfo:v1
docker start app
```
Container 계층구조 

* Layer 1 : Physical Infrastructure [Raw Computer, Network, Storage ]
* Layer 2 : Virtual Infrastructure [vShpere, EC2, GCP, Azure, OpenStack]
* Layer 3 : Operating System [Ubuntu, RHEL, CoreOS, Unikernels]
* Layer 4 : Container Engine : Docker, Rocket, RunC(OCI), Osv, LXC, LXD
* Layer 5 : Orchestration/Scheduling Service Model [K8s, Docker Swarm, Marathon/Mesos, Nomad, Diego ..]\
* Layer 6 : Development Workflow Opinionated Containers [OpenShift, Cloud Foundary, Docker Cloud, Deis, Flynn ...]



