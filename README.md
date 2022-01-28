# Ethical_Hacking_Sheet_Cheat
Needed (or usefull to remember) command line or tools to use during pentest or ethical hacking (e.g. Hack-the-box, Root-me...)

## Template
```console
ethicalhacker@kali:~$
```

## usefull links
### github repo
[SecLists](https://github.com/danielmiessler/SecLists)

[PEASS-ng](https://github.com/carlospolop/PEASS-ng)

[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)

## Run openvpn in daemon
```console
ethicalhacker@kali:~$ sudo openvpn --config openvpn-file.ovpn --daemon
```
```console
ethicalhacker@kali:~$ sudo killall openvpn
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
ethicalhacker@kali:~$ nmap ADD USEFULL COMMANDS
```
## dirb
```console
ethicalhacker@kali:~$ sudo dirb http(s)://example.com
```
## gobuster    
```console
ethicalhacker@kali:~$ sudo gobuster dir/dns/s3/vhost http(s)://example.com
```

## Spawn a TTY shell from an interpreter (there exist other alternative)
```console
ethicalhacker@kali:~$ python -c 'import pty; pty.spawn("/bin/sh")'
```
