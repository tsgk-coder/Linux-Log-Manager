# Linux Log Yönetimi

``
rsyslog
``

# Yerel log kaynakları

```
└─$ /var/log/apache2/access.log
    /var/log/auth.log
    /var/log/audit/audit.log 
└─$ audit
    sudo apt install auditd
    sudo systemctl start auditd.service
    sudo systemctl enable auditd.service
    sudo nano /etc/audit/auditd.conf    
    sudo nano /etc/audit/audit.rules
    sudo systemctl restart auditd.service
    sudo ausearch -m AVC                 
    sudo chmod +x /etc/audit/audit.log    
    sudo tail -f /etc/audit/audit.log
```

# Linux Güvenlik Ürünleri

```
└─$ Firewall (Gufw)
└─$ Elasticsearch
└─$ 
```
