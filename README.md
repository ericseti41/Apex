# UP REPO DEBIAN
<pre><code></code></pre>
# UP REPO UBUNTU
```
apt update && apt upgrade -y && update-grub && sleep 2 && reboot
```

### INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/ericseti41/Apex/main/install.sh && chmod +x install.sh && ./install.sh
```
### KALO STATUS HPOXY MERAH
```
rm -fr /etc/haproxy/hap.pem
cat /etc/xray/xray.crt /etc/xray/xray.key | tee /etc/haproxy/hap.pem
systemctl daemon-reload
systemctl restart haproxy
```
## UPDATE SCRIPT
```
wget -q https://raw.githubusercontent.com/ericseti41/Apex/main/update.sh && chmod +x update.sh && ./update.sh
```

### WORK DI OS
- UBUNTU 18 / 20
- DEBIAN 9 / 10
- 

### SUPPORT PORT
```
- SSL/TLS : 443 / 8443
- SSHWS : 80 / 8880 / 8080 / 2082 / 2095 / 2096