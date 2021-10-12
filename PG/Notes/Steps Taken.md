# Proving Grounds - "Machine Name" - 192.168.x.x

# Enumeration
## Nmap
### Inital Scan
Command
```
nmap -A -vv -oA enum/nmap-initial 192.168.
```

Output
```

```

### Full Scan
Command
```
nmap -A -vv -p- -oA enum/nmap-full 192.168.
```

Output
```

```

## Port 80
### Nikto
Command
```
nikto -h http://192.168. -o enum/nikto.txt
```

Output
```

```

### GoBuster
Command
```
gobuster dir -u http://192.168. -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -o enum/gobuster.txt
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
ifconfig;id;hostname;cat local.txt
```
>

## Root/Admin
Command
```
ifconfig;id;hostname;cat proof.txt
```
>