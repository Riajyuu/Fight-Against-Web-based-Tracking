There is indeed a trunk of ways to track in this part, proxy is generally known to hide it initially (instead of bypassing restrictions). So only those methods reveal your unproxied IP will be discussed here.



#### Adobe Flash Player

Simply disable and/or uninstall it. If you have to use it, set to `click to play` though it is still comprimised sometimes.



#### WebRTC

It can reveal your both unproxied public and local IP (both IPv4/6) without any asking even if you hide yourself into a Tor relay.



Recommended solution: [uBlock Origin](https://github.com/gorhill/uBlock/), in `Settings` tab of extension option page, click `Prevent WebRTC from leaking local IP addresses`.



#### DNS

A very easily missed part is DNS query transfer via SOCKSv5.



Recommended solution: [Pcap DNSProxy](https://github.com/chengr28/Pcap_DNSProxy) or [Simple DNSCrypt](https://www.simplednscrypt.org/). Do note that encrypted DNS traffice can break website CDNs, especially the latter.



#### Java & Silverlight

Well, good luck if you are still struggling with them.