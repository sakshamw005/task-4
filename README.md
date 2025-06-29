# task-4
# 🔥 Firewall Configuration and Testing using UFW (Kali Linux)

## 🎯 Objective
Configure basic firewall rules using UFW to allow/deny traffic, test access via SSH, and understand how firewalls filter network traffic.

---

## 🔧 Commands Used

### 1. Enable UFW
```bash
sudo ufw enable
```
### 2. Allow SSH (Port 22)
```bash
sudo ufw allow 22
```
### 3. Check Current Rules
```bash
sudo ufw status verbose
```
### 4. Block Telnet (Port 23)
```bash
sudo ufw deny 23
```
### 5. Remove the Telnet Rule Later
```bash
sudo ufw delete deny 23
```
