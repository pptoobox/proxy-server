# Proxy Server Setup
## Description
This simple script can easily create an HTTP(s) proxy server without hassle. All you need is a Linux server (preferably Ubuntu) and run the script (instructions given below). Congratulations, now you have an up-and-running proxy server.

> `Make sure you have root access to the server.`

## Requirments
+ A VPS Server.
+ Basic terminal skills.

## Instructions
1. Connect to your server via SSH.
2. Then run the command:
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/pptoobox/proxy-server/main/proxy-server-setup.sh)"
```
3. You should get your credentials at the bottom of your terminal output.

> **Note: The proxy server will use port _`443`_ and _`Google Public DNS`_ by default. However, you can change that easily by following the steps below.**

### To change the default port:
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/pptoobox/proxy-server/main/change-proxy-port.sh)"
```

### To change DNS Server:
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/pptoobox/proxy-server/main/change-dns.sh)"
```
