# BU-EC521---Project-on-Replay-Attack-SDR
## Wireless Security: From 1s and 0s to invisible espionage threat

### What is the problem that you are trying to solve? Why is it important?
Nowadays, we’re using thousands of wireless devices and there are 100s of them that transmit information without proper security protocols in place. Firewalls and rules are in place, intrusion detection systems are running, and all industry best practices are being followed. Great, but what about Radio Frequency attacks? They nimbly sidestep all of that.

It's that variety of different ways in which RF can be used that make it important for security professionals to understand something of the basics of radio. In the past, it was all about how to get an RJ45 connection to a network. Today, it is all about intercepting radio signals such as Bluetooth, Wi-Fi, 4G, and now 5G. Once transmitted into space, a radio signal can be intercepted by anyone with a receiver tuned to the proper frequency. Building or buying receivers for sniffing is easy, and the new technology market is making it more accessible. We’ll be looking at wireless vulnerabilities which commonly exist in IoT Devices, and possible ways to mitigate them.

### How will you mitigate the problem? What kind of techniques/ technologies will you use? 
It is anticipated that by 2025 more than 50 billion IoT devices will be connected and out that over 65% use some sort of wireless technology to transfer information, although replay attack is good PoC with ever-changing technologies we need to find alternative ways for secure communication. One of the basic examples is the time constraint between the transmitter and receiver reception, to identify rogue devices based on the anticipated power of signals... As if any evil device will transmit the same information with SDR, it might be possible that it's slightly high-powered than what the key(victim device) is actually designed for. There are other alternative ways of mitigating and addressing the issue by incrementing the signal every time, the first time if data is (n) then the next key will be (n+1) and so… In this case even though the attacker sniffed the signal (n) when he replays this the device will not respond as it’s now set to listen for (n+1). 


