# HTML Injection Attack

This lab explores HTML Injection attacks using the intentionally vulnerable **bWAPP** application inside a secure lab environment.

### Objective
- Run bWAPP using Docker
- Identify HTML injection vulnerabilities
- Perform a reflected HTML injection attack
- Capture and analyze malicious payloads

### Lab Environment
- VirtualBox + Kali Linux
- Docker
- bWAPP from PentestLab

### Attack Flow
1. Launch vulnerable app (bWAPP) using Docker
2. Identify injection points (reflected GET)
3. Inject malicious HTML (`<form>` with `POST` to attacker)
4. Use Netcat to listen on a port and capture data
   
### Resources
- [PentestLab GitHub](https://github.com/eystsen/pentestlab)
- [bWAPP Docker](https://hub.docker.com/r/raesene/bwapp)
- [Kali Linux](https://www.kali.org/)

> ⚠️ For educational purposes only. Do not attempt outside of a controlled lab!

