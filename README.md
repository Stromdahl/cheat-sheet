## Linux 

#### Systemd
list running services ` systemctl list-units --type=service --state=running `

## Commands
#### General
Get the number of installed packeges on the system
` dpkg-query -W | wc -l ` Debian based system
` yum list installed | wc -l ` RPM-Based System (not tested)

#### dd
dd if=debian-11.6.0-amd64-netinst.iso of=/dev/sdb bs=4M

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


## Useful Links
[SSH Bastion Host Best Practices](https://goteleport.com/blog/security-hardening-ssh-bastion-best-practices/)
