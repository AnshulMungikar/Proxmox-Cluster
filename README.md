# Proxmox-Custer
I am trying to make a proxmox cluster.
# What is a Proxmox Cluster?
A Proxmox cluster is a group of two or more Proxmox VE (Virtual Environment) nodes (servers) that are connected together so they can be managed centrally and share resources.
### Why is clustering important?
1. If we have 2 or more nodes (servers) we would have to log in to each node and make changes. With a cluster we only have to log in into one node and be able to manage all the nodes.
2. If one node (server) crashes, the cluster can automatically restart its VMs/containers on another healthy node. [Will be trying this]
3. If we need nore compute power or storage than our current node we just have to add another node to the cluster, so that we can share the resources. [Will be trying this].

# Proxmox Cluster Lab

This project documents my setup and experiments with building a **Proxmox VE cluster** at home.  
It currently consists of 2 nodes:

- Node 1: Main Proxmox server (running production VMs & containers) (pve)
- Node 2: Fresh Proxmox install (cluster member) (pve1)

The goal is to:
- Create a Proxmox cluster
- Learn about centralized management
- Explore migration and shared storage options (NFS/CEPH)

---

## Steps
- [01 Prerequisites](Docs/01_Prerequisites.md)
- [02 Node Setup](Docs/02_Node-Setup.md)
- [03 Cluster Creation](Docs/03_Cluster-Creation.md)

---
