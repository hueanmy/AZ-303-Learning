# Implement Virtual Networking

## Virtual Networking

### Azure Virtual Networking

- The first thing you should think about isn't the virtual machine - it's the network.
- Virtual networks (VNets) are used in Azure to provide private connectivity between Azure Virtual Machines and other Azure services. VMs and services that are part of the same virtual network can access one another. By default, services outside the virtual network cannot connect to services within the virtual network. You can, however, configure the network to allow access to the external service, including your on-premises servers.
- Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. VNet enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks. VNet is similar to a traditional network that you'd operate in your own data center, but brings with it additional benefits of Azure's infrastructure such as scale, availability, and isolation.

### VNet concept

- Address space: When createing a VNet, you must specify a custom private IP address space using public and private(RFC 1918) addresss.


## Virtual Network Peering

## Implement VNet Peering

## Review & Questions