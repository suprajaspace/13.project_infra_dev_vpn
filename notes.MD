https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/key_pair


VPN instance created, need to configure 

click on vpn instance : 
check security group rules

to connect vpn ' ssh  -i ~/.ssh/openvn openvnas@<public IP>
openvpnas  is default user to open instance
 
 click yes
 all default options

 port numbers agreed

 press enter for all default settings
password: caps ,special character , 8 characters


Admin UI : to access  openVPI 

username :openapi
pass word: 

agree 




VPN settings

should client internet traffic be routed through the VPN:  Yes

DNS settings
Have clients use specific DNS servers :yes
for practice using

Primary DNS server 
8.8.8.8
Secondary DNS server
8.8.4.4

save settings
update runnung server

to connect to vpn server using client called openvpn connect client

openvpn connect v3 download and install

openvpn GUI

URL :  client UI url
Next

username:openvpn
password

Import

Enter password
Next

connecting

check my ip address

now same IP address as vpn IP address,location changed to aws selected region,

now can access application load balancer directly
we give port no 80 access from alb to vpn, so can access CNAME address directly in browser in PC.

1. steps 

VPN SG 
VPN SG rules
create key pair for vpn access
VPN instance with open VPN
openvpnas is the username'
configure with default options
https://xx.xxx.xxx.xx:943/admin
openvpn, Password@123

dowmload openvpn connect
https://xx.xxx.xxx.xx:943
openvpn, Password@123

