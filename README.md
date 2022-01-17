# Ethical_Hacking_Sheet_Cheat
Needed (or usefull to remember) command line or tools to use during pentest or ethical hacking (e.g. Hack-the-box, Root-me...)

## Template
```console
ethicalhacker@kali:~$
```

## usefull links
# githib repo
[SecLists](https://github.com/danielmiessler/SecLists)



## Run openvpn in daemon
```console
ethicalhacker@kali:~$ sudo openvpn --config openvpn-file.ovpn --daemon
```
## Debian-based distro .deb installation
```console
ethicalhacker@kali:~$ sudo dpkg -i <path/of/deb-file>
```
## Some DNS issues
```console
ethicalhacker@kali:~$ sudo nano /etc/hosts

127.0.0.1       localhost
127.0.1.1       kali
<IP address>	<DNS name>

```
## nmap
```console
ethicalhacker@kali:~$ namp ADD USEFULL COMMANDS
```
## dirb
```console
ethicalhacker@kali:~$ sudo dirb http(s)://example.com
```
## gobuster    
```console
ethicalhacker@kali:~$ sudo gobuster dir/dns/s3/vhost http(s)://example.com
```
