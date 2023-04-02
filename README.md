# iplist
this is spam and hack block ip lists. We base our collection on a list of IPs that provide abuse for firewalls and mail systems
The IP list range for mail system abuse. We collect according to the abuse IP we actually encounter, and support IPv4 and IPv6. Usually, the minimum range of ipv4 is /24, and IPv6 /48 If according to our judgment, we will carry out a larger range .For example, the IP range of some large operators in China. /16 Because they are usually used for dynamic users, they are not controlled.

Instructions:

Import the ip range in mail.txt to the firewall to block the ip range in the list from entering your mail system port.
For example port 25 465 587 143 993 995
这是IP黑名单, 所有与邮件通讯有关的违法行为IP将被记录到此列表,你可以将此列表直接放入你的防火墙,阻挡其访问你的邮件服务器. 为什么有使用/16很大IP范围，因为根据我们的了解这些IP大概率不会用于正规服务器用途,所以直接阻挡是没有问题. 如果有任何报告ip是正规服务器用途,请联系我们予以调查. 所有数据均为我们自己记录收集,没有采用第三方数据.
