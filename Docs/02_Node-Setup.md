### Main Proxmox
1. Installed proxmox.
2. Hostname: pve.bbrouter 

### Secondary Proxmox
1. Installed proxmox
2. Hostname: pve1.bbrouter


### Making the Servers resolve eachother:
#### This is done on the old proxmox server(already has services running):
     Its ip address is 192.168.1.123
     

![pve → pve1 hosts config](../images/etc-hosts.png)

![Adding-pve1-to-pve](Images/Adding-pve1-to-pve.png)



So, now when i try to  `ping pve1` i am actually pinging the new proxmox machine and I get a response.

#### This is done on the new proxmox (to be clustered):
     Its ip address is 192.168.1.124   

![Adding-pve-to-pve1](Images/adding-pve-to-pve1.png)

