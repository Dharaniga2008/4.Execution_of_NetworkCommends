# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Dharaniga>ipconfig

Windows IP Configuration


Unknown adapter McAfee VPN:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2401:4900:ca9c:5522:7bbc:f62b:b4a:7686
   Temporary IPv6 Address. . . . . . : 2401:4900:ca9c:5522:bd79:66b1:52e1:8518
   Link-local IPv6 Address . . . . . : fe80::517f:48c2:effc:c9c0%11
   IPv4 Address. . . . . . . . . . . : 10.252.247.8
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::e88b:88ff:fe1e:ce9a%11
                                       10.252.247.203

C:\Users\Dharaniga>hostname dharaniga
sethostname: Use the Network Control Panel Applet to set hostname.
hostname -s is not supported.

C:\Users\Dharaniga>macaddress
'macaddress' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Dharaniga>getmac

Physical Address    Transport Name
=================== ==========================================================
00-FF-E2-A8-DD-BE   Media disconnected
F8-3D-C6-07-50-B6   \Device\Tcpip_{8753A1EC-B5B1-44EE-9BA0-3A58A5BF4CC8}

C:\Users\Dharaniga>google.com
'google.com' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Dharaniga>ping google.com

Pinging google.com [2404:6800:4007:835::200e] with 32 bytes of data:
Reply from 2404:6800:4007:835::200e: time=103ms
Reply from 2404:6800:4007:835::200e: time=106ms
Reply from 2404:6800:4007:835::200e: time=115ms
Reply from 2404:6800:4007:835::200e: time=128ms

Ping statistics for 2404:6800:4007:835::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 103ms, Maximum = 128ms, Average = 113ms

C:\Users\Dharaniga>tracert google.com

Tracing route to google.com [2404:6800:4007:80f::200e]
over a maximum of 30 hops:

  1   110 ms     5 ms     4 ms  2401:4900:ca9c:5522::3f
  2   142 ms   102 ms    27 ms  2401:4900:1:a829::2
  3   132 ms    28 ms    63 ms  2401:4900:1:a88a::4
  4    47 ms   110 ms    50 ms  2401:4900:1:a88b::1
  5     *        *        *     Request timed out.
  6    67 ms   101 ms    20 ms  2404:a800:3a00:1::651
  7   130 ms    91 ms     *     2404:a800::92
  8    96 ms   197 ms   101 ms  2404:6800:8202:380::1
  9    97 ms    97 ms    99 ms  2404:6800:8202:380::1
 10    98 ms    98 ms    97 ms  2001:4860:0:1::5650
 11   108 ms    90 ms    99 ms  2001:4860:0:1::4878
 12   108 ms   100 ms    99 ms  2001:4860:0:1::880d
 13   103 ms   100 ms    98 ms  2001:4860:0:1::55c9
 14   122 ms    31 ms    62 ms  lcmaaa-au-in-x0e.1e100.net [2404:6800:4007:80f::200e]

## Result
Thus Execution of Network commands Performed 
