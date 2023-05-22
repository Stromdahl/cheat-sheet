# Linux 

**Get the number of installed packeges on the system**

``` Bash
dpkg-query -W | wc -l # Debian based Systems
yum list installed | wc -l # RPM-Based Systems (not verified to work)
``` 

**List running services on Systemd**
``` Bash
systemctl list-units --type=service --state=running 
```

## Commands

#### dd
``` Bash
dd if=debian-11.6.0-amd64-netinst.iso of=/dev/sdb bs=4M
```

## Markdown
[Cheet Sheet](https://www.markdownguide.org/cheat-sheet/)
Link
` [title](https://www.example.com) `

Heading 	
```
# H1
## H2
### H3
```

## SSH
### Security
[Mozilla OpenSSH recomendations](https://infosec.mozilla.org/guidelines/openssh)
[SSH Bastion Host Best Practices](https://goteleport.com/blog/security-hardening-ssh-bastion-best-practices/)

## Other cheat-sheets
https://github.com/ruanbekker/cheatsheets
