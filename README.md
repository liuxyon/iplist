# iplist
this is spam and hack block ip lists. We base our collection on a list of IPs that provide abuse for firewalls and mail systems
The IP list range for mail system abuse. We collect according to the abuse IP we actually encounter, and support IPv4 and IPv6. Usually, the minimum range of ipv4 is /24, and IPv6 /48 If according to our judgment, we will carry out a larger range .For example, the IP range of some large operators in China. /16 Because they are usually used for dynamic users, they are not controlled.

Instructions:

Import the ip range in mail.txt to the firewall to block the ip range in the list from entering your mail system port.
For example port 25 465 587 143 993 995
