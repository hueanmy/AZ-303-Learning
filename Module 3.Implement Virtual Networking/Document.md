# Implement Virtual Networking

## Virtual Networking

### Azure Virtual Networking

- The first thing you should think about isn't the virtual machine - it's the network.
- Virtual networks (VNets) are used in Azure to provide private connectivity between Azure Virtual Machines and other Azure services. VMs and services that are part of the same virtual network can access one another. By default, services outside the virtual network cannot connect to services within the virtual network. You can, however, configure the network to allow access to the external service, including your on-premises servers.
- Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. VNet enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks. VNet is similar to a traditional network that you'd operate in your own data center, but brings with it additional benefits of Azure's infrastructure such as scale, availability, and isolation.

### VNet concept

- Address space: When createing a VNet, you must specify a custom private IP address space using public and private(RFC 1918) addresss. 
- Subnets: 
- Regions:
- Subscription

-> IP public mặc định là dynamic, nếu muốn dùng static thì trả phí
-> If xài máy ảo mà sửa trong card mạng thì không được mặc dù gán tĩnh
-> Trong virtual thì mặc định dùng ip private, còn ip public để bên ngoài truy cập vào
-> Point to site: 
-> Site to site:
-> ExpressRoute: thuê đường truyền riêng thì dài

-> VPN: tốn phí thuê vpn gateway -> dữ liệu được mã hoá.
-> Peering: không phải thuê thiết bị -> không tốn chi phí

-> Filter network: network security groups hoặc network virtual app

-> Peering ko có tính chất bắc cầu, nếu muốn bắc cầu dùng vpn 

## Virtual Network Peering

-> Cùng một thời điểm peering thì có 2 đường truyền: allow gateway transit và use remote gateways
-> 


## Implement VNet Peering

## Review & Questions
