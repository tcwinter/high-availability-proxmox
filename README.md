# proxmox
ookokokk

I have a proxmox server. 

I created 3 VMs and booted proxmox onto them. 

They gave a message, I believe this is because they're nested VMs and may not be as efficient as they could be if I had newer CPUs, but I bought this Dell on the cheap. 

I created a cluster named "rick" because that's what my friends told me to name it. 

I joined all my nodes into the cluster

When I created the pve's I gave them all an additional disk, so I could configure ceph, distributed storage for better failovers/redundancy. 

Then I started initializing ceph. 

Basic config for each. 

Created ceph pool "coolpool" for distributed storage.

Created linux server in my ceph pool. 
