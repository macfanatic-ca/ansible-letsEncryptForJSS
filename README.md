# Let's Encrypt for Jamf Pro

## Function
Configures the Certbot client, renewal script, and cron job for automatic SSL certificate renewal.

## Vault
```
---
letsEncryptForJSS_email: jdoe@example.com
```

## Tested Environment(s)
RHEL 7 & CentOS 7

## Changelog

**v2.0 (2017-07-02)**
* Rewritten for easy renewals
* Removed deprecated `certbot` flags  

**v1.0 (2016-02-06)**
* Original Release
