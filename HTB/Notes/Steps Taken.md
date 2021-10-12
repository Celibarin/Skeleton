# Hack the Box - "Machine Name" - 10.10.10.x
# Enumeration
## Nmap
### Inital Scan
Command
```
nmap -A -vv -oA enum/nmap-initial 10.10.10.
```

Output
```

```

### Full Scan
Command
```
nmap -A -vv -p- -oA enum/nmap-full 10.10.10.
```

Output
```

```

## Port 80
### Nikto
Command
```
nikto -h http://10.10.10. -o enum/nikto.txt
```

Output
```

```

### GoBuster
Command
```
gobuster dir -u http://10.10.10. -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -o enum/gobuster.txt
```

Output
```

```
 
---

# Vulnerabilities


---

# Privilege Escalation


---

# Loot
## User
Command
```
ifconfig;id;hostname;cat user.txt
```
>

## Root/Admin
Command
```
ifconfig;id;hostname;cat root.txt
```
>
