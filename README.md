## Small Office Network Design

This project is to create a Local Area Network design(Virtually) for small office using Cisco Packet Tracer. Starting with Development, Sales & Marketing and Server departments where i am going to gradually add more security features to make it more efficient over time.

- I used a layer 3 switch to use as Gateway Device to reduce traffic which are expected to carry out both routing and switching functionalities.
- I also attached a system file where i did did the same with a layer 2 switch to cut cost.

## Case Study and Requirements

The network includes three departments (IT/Server, Development, Sales & Marketing) with each on separate subnets and VLANs. Each department needs its own subnet. Here is the subnet breakdown based on the base network 192.168.1.0/24.

Each department is allocated 64 IP addresses (/26 subnet mask), enough to cover most small office requirements. This subnetting keeps departments isolated within their IP range and minimizes broadcast traffic.

## Subnetting

|Department|Subnet Address|Subnet Mask|Host Range|VLAN ID| 
| :-------- | :-------    | :------   | :------  | :----- 
| Sales | 192.168.1.0/26 | 255.255.255.192 | 192.168.1.1 - 192.168.1.62 | 10
Development| 192.168.1.64/26 | 255.255.255.192 | 192.168.1.65 - 192.168.1.126 | 20
Admin | 192.168.1.128/26| 255.255.255.192 | 192.168.1.129 - 192.168.1.190 | 30 

## Features
- Separated VLAN's for Departments.
- Layer 3 Switch used as Gateway Device to reduce traffic.
- Wireless Access Points are Configured in separate VLAN for Guest usage.
- Creating VLANs and assigning ports VLAN numbers.
- Remote access of L3 switch and Router had been enabled Security is Ensured in remote access.
- Configuring Dedicated DHCP Server device to provide dynamic IP allocation.
- Host Device Configurations.
- Configuring WLAN or wireless network (Cisco Access Point).
- Design is Scalable Upto More the 60 Computers.


## Design
![Design Images](https://github.com/ReshadSadik/Small-Office-Network-Guide/blob/main/Images/remote-new-connection-L3.png)
