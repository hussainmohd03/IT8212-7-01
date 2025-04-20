---
description: This template allows you to create 2 Virtual Machines in a VNET and under an internal Load balancer and configure a load balancing rule on Port 80. This template also deploys a Storage Account, Virtual Network, Public IP address, Availability Set and Network Interfaces.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: 2-vms-internal-load-balancer
languages:
- bicep
- json
---
# IT8212 - LAB 7-03 Updated
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhussainmohd03%2FIT8212-7-01%2Fmain%2Fazuredeploy.json)

This template also deploys a Storage Account, Virtual Network, Availability Set and Network Interfaces.

The Azure Load Balancer is assigned a static IP in the Virtual Network and is configured to load balance on Port 80.

`Tags: Microsoft.Storage/storageAccounts, Microsoft.Compute/availabilitySets, Microsoft.Network/virtualNetworks, Microsoft.Network/networkInterfaces, Microsoft.Network/loadBalancers, Microsoft.Compute/virtualMachines`
