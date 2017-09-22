# Getting started with Proxy.sh VPN

This basic documentation provides a good summary of all the things you need to know for a good experience with Proxy.sh.

## The basics

The easiest way to connect securely with Proxy.sh is to download Safejumper, our custom VPN client at https://proxy.sh/software

You can also use our online wizard to get a recommendation about a simple method to connect at https://proxy.sh/start

Find out how to set up our proxy tunnels using our easy-to-follow illustrated guides are at https://proxy.sh/guides & https://proxy.sh/getstarted

For support, billing and sales related inquiries please submit a ticket at https://proxy.sh/help

Last but not least, you should always check your online security leaks at https://leaktest.online/

## Network details

### OpenVPN (RSA-4096)

OpenVPN UDP Ports: 1443 (default), 53, 1194, 8080 or 9201

OpenVPN TCP Ports: 843 (default), 80, 110 or 443

You can download the openvpn.ovpn and .crt files at https://proxy.sh/configs

(The .crt file is in the same directory as the .ovpn ones)

### OpenVPN (ECC)

OpenVPN UDP Port: 465 

OpenVPN TCP Port: 465 

You can download the openvpn.ovpn and .crt files at https://proxy.sh/configs

(The .crt file is in the same directory as the .ovpn ones)

### OpenVPN (ECC+XOR)

OpenVPN UDP Port: 995  

OpenVPN TCP Port: 995 

You can download the openvpn.ovpn and .crt files at https://proxy.sh/configs

(The .crt file is in the same directory as the .ovpn ones)

### OpenVPN (TOR's obfsproxy)

OpenVPN UDP Port: 888 (obfs2), 898 (obfs3) or 988 (scramblesuit)

OpenVPN TCP Port: 888 (obfs2), 898 (obfs3) or 988 (scramblesuit)

You can download the openvpn.ovpn and .crt files at https://proxy.sh/configs

(The .crt file is in the same directory as the .ovpn ones)

### PPTP

PPTP TCP Port: 1723

You can download the PPTP pkb file (if needed) at https://proxy.sh/configs

### L2TP

L2TP Secret: security

L2TP UDP Port: 1701

You can download the L2TP pbk file (if needed) at https://proxy.sh/configs

### SoftEther

SoftEther Secret: security

SoftEther Ports: 5555, 992 or 8787 

### OpenSSL

You can download the OpenSSL .ssl file (if needed) at https://proxy.sh/proxysh.ssl

## Config generator

You can also generate any configuration files for OpenVPN at https://proxy.sh/config

## Security notice

We strongly recommend that you only use OpenVPN. All other protocols such as PPTP, L2TP, SOCKS or CGIProxy are using weak encryption methods, and it is rather simple to decrypt them. If you connected to them, change your VPN password. You should always prefer OpenVPN with the strongest encryption method whenever you can. We also invite you to protect yourself against any potential network leak. 

https://proxy.sh/leaks
https://leaktest.online/

## Security extras

* OpenSSL
 
https://proxy.sh/panel/knowledgebase/56/OpenSSL

* DNS & DNSCrypt

https://proxy.sh/panel/knowledgebase/39/DNS
https://proxy.sh/panel/knowledgebase/53/DNSCrypt

* SOCKS

https://proxy.sh/panel/knowledgebase/40/SOCKS

* HTTP

https://proxy.sh/panel/knowledgebase/41/HTTP

* ECC & ECC+XOR

https://proxy.sh/panel/knowledgebase/58/ECC-Diffie-Hellman
https://proxy.sh/panel/knowledgebase/59/ECC-plus-XOR-Scramble

* TOR & Obfsproxy

https://proxy.sh/panel/knowledgebase/42/TOR
https://proxy.sh/panel/knowledgebase/54/Obfsproxy-Stealth

* SoftEther

https://proxy.sh/panel/knowledgebase/57/SoftEther

* Jabber

https://proxy.sh/panel/knowledgebase/50/Jabber

* Cryptocat

https://proxy.sh/panel/knowledgebase/51/Cryptocat

* Pastebin

https://paste.proxy.sh/

* API

https://proxy.sh/panel/knowledgebase/52/API

* Anonymous Tokens

https://proxy.sh/panel/knowledgebase/55/Tokens

## Always more extras !

You can check network status @ https://proxy.sh/status

You can generate an OpenVPN configuration @ https://proxy.sh/config

You can test your network speeds @ https://proxy.sh/speedtest

You can test your network security @ https://proxy.sh/check

You can whitelist your email server @ https://proxy.sh/email

You can input your custom domain @ https://proxy.sh/domains

Finally, you can check all extra products @ https://proxy.sh/extras
