19 Customizable honeypots for monitoring network traffic, bots activities, and username\password credentials (DNS, HTTP Proxy, HTTP, HTTPS, SSH, POP3, IMAP, STMP, RDP, VNC, SMB, SOCKS5, Redis, TELNET, Postgres, MySQL, MSSQL, Elastic and ldap)

If you want to implement the honeypots in your project, check [QeeqBox honeypots](https://github.com/qeeqbox/honeypots)
## Grafana Interface
<img src="https://raw.githubusercontent.com/qeeqbox/chameleon/master/readme/intro.gif" style="max-width:768px"/>

#### NMAP Scan
<img src="https://raw.githubusercontent.com/qeeqbox/chameleon/master/readme/nmap_scan.png" style="max-width:768px"/>

#### Credentials Monitoring
<img src="https://raw.githubusercontent.com/qeeqbox/chameleon/master/readme/creds_monitoring.png" style="max-width:768px"/>

The Grafana interface http://localhost:3000 will open automatically after the initialization process (username is changeme457f6460cb287 and password is changemed23b8cc6a20e0). If you don't see the Chameleon dashboard, click on the search icon in the left bar and add it.

## Requirements (Servers only)
```bash
apt-get update -y && apt-get install -y iptables-persistent tcpdump nmap iputils-ping python python-pip python-psycopg2 lsof psmisc dnsutils
pip install scapy==2.4.4 netifaces==0.10.9 pyftpdlib==1.5.6 sqlalchemy==1.3.23 pyyaml==5.4.1 paramiko==2.7.1 impacket==0.9.22 twisted==20.3.0 psutil==5.8.0 requests==2.25.1 redis==3.5.3 mysql-connector-python==8.0.23 pygments==2.5.2
pip install -U requests[socks]
pip install -Iv rsa==4.0
pip install rdpy==1.3.2
```
