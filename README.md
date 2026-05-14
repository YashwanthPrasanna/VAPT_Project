
# VAPT Project Using Metasploitable2 and Nmap

## Objective
This project demonstrates Vulnerability Assessment and Penetration Testing (VAPT) in a controlled lab environment using Metasploitable2 and Nmap.

---

## Tools Used
- VirtualBox
- Metasploitable2
- Nmap

---

## Lab Environment
A vulnerable Linux virtual machine was configured using VirtualBox for performing cybersecurity testing and vulnerability assessment.

---

## Methodology

### 1. Reconnaissance
Identified target machine IP address using:

```bash
ifconfig
````

---

### 2. Run Below Commands in Terminal

#### Check Nmap Installation

```bash
nmap
```

#### Verify Target System Connectivity

```bash id="2q2c2h"
ping 192.168.56.101
```

#### Basic Port Scanning

```bash id="n2f65v"
nmap 192.168.56.101
```

#### Advanced Service Enumeration

```bash id="zg3qvk"
nmap -Pn -sC -sV 192.168.56.101
```

---

## Findings

### Open Services Identified

* FTP
* SSH
* Telnet
* HTTP
* SMB
* MySQL
* PostgreSQL
* VNC

### Security Weaknesses

* Anonymous FTP login enabled
* Telnet service exposed
* SMB message signing disabled
* Outdated Apache server detected
* Multiple outdated services identified

---

## Conclusion

This project successfully demonstrates practical VAPT methodology including reconnaissance, service enumeration, vulnerability assessment, and security analysis using industry-standard cybersecurity tools.

```
```
