# LazySysOps

## Table of Contents

- [Useful Linux Commands](#useful-linux-commands)
- [Tools for Sysadmins](#tools-for-sysadmins)


## Useful Linux Commands


### Network Troubleshooting

#### Traceroute
Traceroute is used to track the path that packets take from your system to a specified destination.

```bash
traceroute 1.1.1.1
```

MTR (My Traceroute)  
MTR provides real-time network diagnostics, combining the functionality of ping and traceroute.  

```bash
mtr 1.1.1.1
```

Start a simple HTTP server using Python to serve files from a directory.  

```bash
python3 -m http.server 8000
```

Protect your ZIP files with a password using zipcloak.  

```bash
zipcloak file.zip
```

Enter Password: When prompted, enter your desired password.  

Decrypting a ZIP File  
To decrypt a ZIP file, you can use the `-d` option with zipcloak.  

```bash
zipcloak -d file.zip
```

Enter Password: You will be prompted to enter the password to decrypt the file.  



