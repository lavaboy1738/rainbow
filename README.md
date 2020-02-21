# HTTP Notes

http = Hypertext Transfer Protocol 
IP = Internet Protocol 

IP is mainly two things: 
1. how to locate one device 
2. how to package things and communicate with other devices 

the modem can translate signals into signals that your devices can understand, and the router can amplify this signal and spread it over your house. 

router has two IP addresses, one for the intranet and one for the internet. 
Devices within the intranet can access each other, but they can’t directly access the internet. 
Devices on the internet can also directly access each other. Like your router can access Google, but devices on the internet cannot access devices on the intranet. They have to go through the router. 

Special IP:
127.0.0.1 indicates self
localhost is an actual file and you can set the name as anything you like, the default option is 127.0.0.1 localhost.
having only IP address is not enough, you also need a port.
different service requires different kinds of ports. 
http uses 80
https uses 443
FTP uses 21
there are 65535 different ports in total

domain name
a string that ends with .com, .net, .org 

ping, a command to send a request to a website

note that the same IP address can correspond to different domain name.

DNS: domain name system, a system that  connects a domain name to a certain IP address 

URL, uniform resource locator
protocol + domain name/IP + port + path + search string + anchor point

curl command:
curl + url 
-v: verbose
