---
layout: default
---

# <span style="color:#267CB9"> My Homelab </span>
------

## <span style="color:#267CB9"> Personal Development: </span>
-----

* Setup a SOHO network setup consisting of all managed Ubiquiti Unifi gear, 4 main servers, and a Synology NAS. The network is constructed with 1 firewall, 1 switch, and 2 APs and has custom firewall rules are in place to keep guest traffic, IoT devices, and the DMZ traffic isolated from the secure LAN. The servers are an ESXi 8 server and 3 node Highly Available Proxmox Cluster. The ESXi server is the main production machine and is running a Windows Server 2022 VM for testing and network DNS, as well as, a few Debian based VMs to host docker containers for various workloads. Just to name a few containers there are web servers, uptime monitoring, VPNs and remote management. The 3 node Proxmox cluster is primarily set up for learning RHEL, it hosts a couple more Debian based VMs, and allows for the learning of clustered storage through Ceph.

## <span style="color:#267CB9"> Services and Layout: </span>
![Homelab Diagram](./assets/img/Homelab-Diagram.png)

