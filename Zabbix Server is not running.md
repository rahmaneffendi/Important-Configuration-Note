i got that problem, then i realized a have to disable selinux 

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

![Screenshot 2023-04-21 090841](https://user-images.githubusercontent.com/99697182/233533681-d3b53e8c-22ae-45a7-8933-c5b04092e5e7.png)


After

![image](https://user-images.githubusercontent.com/99697182/233533525-35b1e3e7-0dba-4e98-b468-1d2c24151cdf.png)
