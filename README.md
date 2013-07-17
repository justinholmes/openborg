openborg
========
An opensource implementation of Google Borg using Apache ZooKeeper, libvirt and docker.

It aims to provide developers the choice of deploying clusters of applications on either bare metal with docker and virtualized using libvirt (kvm under the hood)
The clusters of applications then communicate with ZooKeeper to announce their locations. Possibly in the future updating load balancers or DNS. 

It aims to deploy, monitor and scale applications on a choice of infrastructure.
