# Azure-ARM-Templates
Examples of Azure ARM Templates - testing/learning

## Deploy-Basic-Windows-Server.json
Deploy a basic Windows Server 2016 virtual machine.

To Do Items:
- Network configuration
- Admin password

---

## Deploy-vNet-With-Subnets.json
Deploys virtual network with 2 subnets; additional subnets can be added. Also includes resource tags.

---

## deploy-vnet-2linuxvm-1winvm.json
This template deploys a virtual network, subnet, 2 CentOS virtual machines, and 1 Windows Server 2016 virtual machine. One of the Linux virtual machines will have a public IP address attached. This is the base template for a project I'm working on to automate deploying an Ansible lab into Azure. The Linux virtual machine with the public IP address will be the Ansible control server while the remaining virtual machines will be test systems to deploy Ansible commands and playbooks against.

To Do Items:
- Add network security group to server with public ip address to allow port 22 for SSH