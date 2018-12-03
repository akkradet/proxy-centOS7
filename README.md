# proxy-centOS7
Fast installation Proxy Using Squid on CentOS 7

Install
=======

Run command (replace *123456* with your password):

```bash
curl -L https://raw.githubusercontent.com/akkradet/proxy-centOS7/master/install.sh | PROXY_PASS=123456 sh
```

After install, you can access your proxy on port **3128**.
User name will be **admin** with your password.


FAQ
===

### How to add new user?

```bash
htpasswd /etc/squid/.htpasswd username
```

Use option **-c** to replace all existed users:

```bash
htpasswd -c /etc/squid/.htpasswd username
```
