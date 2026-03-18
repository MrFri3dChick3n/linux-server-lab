# Linux Server Lab

Hands-on homelab where I practice Linux administration, server setup, troubleshooting, and security.

---

# Linux Server Lab

## Setup
- Ubuntu Server in VirtualBox
- SSH access configured
- Apache installed
- PHP installed
- MariaDB installed

## Skills practiced
- Linux commands
- Service management (systemctl)
- Log analysis (error.log, access.log)
- Firewall (ufw)
- Fail2ban security

## Incident: Fail2ban lockout

### Problem
Lost SSH access after configuring Fail2ban.

### Cause
Fail2ban blocked my IP after multiple failed login attempts.

### Resolution
- Accessed server via VirtualBox console
- Stopped fail2ban service
- Regained SSH access

### Lesson learned
Always whitelist your own IP before testing security tools.

## Future improvements
- Add monitoring tools
- Automate tasks with bash scripts
- Simulate more incidents
