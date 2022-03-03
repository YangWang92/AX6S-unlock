# XIAOMI AX6S UNLOCK TUTORIAL (RB03) 

ONLY FOR RESEARCH AND STUDY! 

CONTACT ME IF YOU HAVE ANY CONCERNS!

for more details https://forum.openwrt.org/t/adding-openwrt-support-for-xiaomi-redmi-router-ax6s-xiaomi-router-ax3200/111085/

1. update firmware to stable version

I download the firmware from here.

https://www.right.com.cn/forum/thread-8173581-1-1.html


2. decrypt password from S/N

copy from namidairo's posts: 

https://forum.openwrt.org/t/adding-openwrt-support-for-xiaomi-redmi-router-ax6s-xiaomi-router-ax3200/111085/16


3. telnet 192.168.31.1

username: root

password: your password

4. You will get a shell after login.

![image](https://user-images.githubusercontent.com/3883941/156363993-b6ea1b61-e1c7-464a-a797-e42e77e0394d.png)


5. enable ssh/uart/telnet

from 

https://forum.openwrt.org/t/adding-openwrt-support-for-xiaomi-redmi-router-ax6s-xiaomi-router-ax3200/111085/18


```bash
nvram set telnet_en=1
nvram set uart_en=1
nvram set ssh_en=1
nvram commit
```

