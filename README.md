docker-vm
=========

This project was created as a placeholder for transparent hypervisor for running Docker on any platform in addition to Linux.

The goal is to create a new command for Docker (docker.io) "docker setup" which will install some kind of hypervisor is a silent mode and configure everything needed to run docker inside a VM on that hypervison. 
For example we can use QEMU (http://wiki.qemu.org/Main_Page)

This idea was described first at http://continuousdelivery.uglyduckling.nl/docker/run-docker-on-any-os-in-a-headless-hypervisor/
