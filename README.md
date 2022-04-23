# Deploying Azure VM as Router

Deploy Azure VM (Linux or Windows) with IP forwarder enabled to be used as Router. All deployments in this document assumes you have already and existing Virtual Network (VNET) and Subnet.

## Deploy Linux VM as Router (IPv4 and IPv6) + NAT to Internet

This template deploys a Linux Router (Ubuntu 18.04-LTS) to an existing Virtual Network (VNET)/Subnet using a Single NIC + IP Forwarding Enabled.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdmauser%2FAzureVM-Router%2Fmaster%2FLinuxRouter.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fdmauser%2FAzureVM-Router%2Fmaster%2FLinuxRouter.json)

## Deploy Windows VM as Router (IPv4 and IPv6)

This template deploys a Windows (Server 2019 Core - Small Disk) Router to an existing Virtual Network (VNET)/Subnet using a Single NIC + IP Forwarding Enabled.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdmauser%2FAzureVM-Router%2Fmaster%2FWinRouter.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fdmauser%2FAzureVM-Router%2Fmaster%2FWinRouter.json)

## Roadmap

- Add VMSS option for both Linux and Windows deployments
- Add Accelerated Networking option
- Make Public IP optional, enable or disable it (Currently deploys with Public IP assigned)
