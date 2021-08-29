# Venom
![venom](https://i.ibb.co/M9FNKgM/snake-6470753.png)

#### Offensive Security Tool for Vulnerability Scanning & Pentesting
![os](https://img.shields.io/badge/OS-Linux,%20Windows-green.svg)
[![pythonver](https://img.shields.io/badge/python-3.6%2B-green.svg)](https://www.python.org/downloads/release/python-3614)
[![License: GPLV3](https://img.shields.io/badge/License-GPLv3-green.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

##### Features
- [x] In its current state, it will only work with torrc `MAX CIRCUIT DIRTINESS` of 10
- [x] Cloudflare Resolver [Cloudbuster]
- [x] LFI->RCE and XSS Scanning [LFI to RCE & XSS]
- [x] SQL Injection Vuln Scanner [SQLi]
- [x] Extremely Large D0rk Target Lists
- [x] Detects known WAFs
- [x] AdminPage Finding
- [x] Vulnerable FTPs Scanner [Toxin]
- [x] DNS Bruteforcer
- [x] Python 3.6 asyncio based scanning
- [x] Cloudflare resolver
- [x] Extremely quick "Toxin" Vulnerable IP scanner to scan potentially millions of ips for known vulnerable services.
- [x] Largest and most powerful d0rker online, searching 14k+ dorks over several engines at once.
- [x] Free and Open /src/
- [x] Cross-platform Python-based toolkit
- [x] Licensed under GPLv3
- [x] Built by hackers with full transparency

![Example of SQLi Dorker](https://github.com/v3n0m-Scanner/V3n0M-Scanner/blob/master/src/AnimatedDemo.gif?raw=true "Example of Dorker Features")

## Install note

Pull it from [Docker Hub](https://hub.docker.com/repository/docker/vittring/venom):
```bash
docker pull vittring/venom:latest
```
or build it from here:
```bash
docker build -t vittring/venom:latest .
docker run -ti vittring/venom:latest
```

Ubuntu users:
Please make sure you `sudo apt-get install python3-bs4` | `apt-get install python3-setuptools`

Kali users:
Please `apt-get install python3-dev` | `apt-get install python-dev`

## Contact Information:
    Submit a bug report/pull request with prefix "Query" at the start.

## Credits to:
    - Architect for the initial encouragement and support in V3n0ms early days
    - SageHack for allowing Cloudbuster to be adapted for use within V3n0M
    - D35m0nd142 for allowing Collaboration and the use of LFI Suite within V3n0M
    - b4ltazar & all members of darkc0de.com for inspiring the project with darkd0rk3r

## Make Love and Smoke Trees.

