#### Creating cluster on pve

On **Node 1** (your current running server):
Run  `pvecm create cluster`
Check cluster status: `pvecm status`

![Cluster-status](Images/cluster-status.png)




#### Joining the Second Node
Do this on the new proxmox machine (Freshly installed proxmox)
`pvecm add 192.168.1.123`
![Adding pve1 to cluster](Images/Adding-pve1-to-cluster.png)

### If the Clustering is successful we will see:
![Final-Result](Images/Final-Result.png)

Where `pve` is the current running server and the `pve1` is the clustered server.







