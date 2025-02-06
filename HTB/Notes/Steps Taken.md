# Hack the Box - "Machine Name" - 10.10.11.x
# Enumeration
## Nmap
### Inital Scan
Command
```
nmap -sC -sV -vv 10.10.11.
```

Output
```

```

### Full Scan
Command
```
nmap -sC -sV -vv -p- 10.10.11.
```

Output
```

```

### UDP Scan
Command
```
nmap -sU -vv 10.10.11.
```

Output
```

```

## Port 80
### Nikto
Command
```
nikto -h http://10.10.11.
```

Output
```

```

### ffuf
Command
```
ffuf -ic -recursion -r -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -u http://10.10.11.00/FUZZ
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
``
>

## Root/Admin
Command
```
ifconfig;id;hostname;cat root.txt
```
``
>
