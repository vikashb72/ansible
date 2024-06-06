# Ansible repo

This roles/playbooks are for my understanding of how stuff works.

## Create gluster vms

cbsd bcreate jname=u22-gfs-1 imgsize=16g vm_cpus=1 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-gfs-1.home.where-ever.za.net \
ip4_addr=192.168.0.11 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-gfs-2 imgsize=16g vm_cpus=1 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-gfs-2.home.where-ever.za.net \
ip4_addr=192.168.0.12 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-gfs-3 imgsize=16g vm_cpus=1 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-gfs-3.home.where-ever.za.net \
ip4_addr=192.168.0.13 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol


## Create gluster vms

cbsd bcreate jname=u22-k8s-cp-1 imgsize=64g vm_cpus=2 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-k8s-cp-1.home.where-ever.za.net \
ip4_addr=192.168.0.15 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-k8s-cp-2 imgsize=64g vm_cpus=2 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-k8s-cp-2.home.where-ever.za.net \
ip4_addr=192.168.0.16 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-k8s-cp-3 imgsize=64g vm_cpus=2 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-k8s-cp-3.home.where-ever.za.net \
ip4_addr=192.168.0.17 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-k8s-nd-1 imgsize=64g vm_cpus=2 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-k8s-nd-1.home.where-ever.za.net \
ip4_addr=192.168.0.18 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-k8s-nd-2 imgsize=64g vm_cpus=2 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-k8s-nd-2.home.where-ever.za.net \
ip4_addr=192.168.0.19 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol

cbsd bcreate jname=u22-k8s-nd-3 imgsize=64g vm_cpus=2 vm_ram=4g \
vm_os_type=linux vm_os_profile=ubuntuserver-amd64-22 \
host_hostname=u22-k8s-nd-3.home.where-ever.za.net \
ip4_addr=192.168.0.20 gw4=192.168.0.1 runasap=0 astart=0 \
interface=re1 imgtype=zvol
