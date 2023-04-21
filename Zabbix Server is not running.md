Zabbix Server Is Not Running

i got that problem, then i realized i have to disable selinux 

```
vim /etc/sysconfig/selinux
```

Change “SELINUX=enforcing” to  “SELINUX=disabled”

Save and exit the file. Then reboot the system.

```
reboot
```

----------------------------------------------------------------------------------------------------------------------------

Before

![WhatsApp Image 2023-04-21 at 10 26 43](https://user-images.githubusercontent.com/99697182/233533961-b6fe8ed3-10b0-44a1-9a7d-2a66a70b65d5.jpeg)


After

![image](https://user-images.githubusercontent.com/99697182/233533525-35b1e3e7-0dba-4e98-b468-1d2c24151cdf.png)
