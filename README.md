VDVESTA是一个小型的shell脚本，为您的CentOS Server Release 7 x86_64自动定制并安装VESTACP

系统要求：CentOS Server 7 x86_64

一键脚本：
----------
curl -L https://github.com/duy13/VDVESTA/raw/master/vdvesta.sh -o vdvesta.sh ; bash vdvesta.sh
----------

脚本界面：

欢迎来到VDVESTA：

一个shell脚本自动定制并安装您的CentOS Server Release 7 x86_64的VESTACP。

感谢您的使用！

你愿意+安装vDDoS代理保护[Y | n]：

vDDoS Proxy Protection install => y

您要安装哪个Web Server版本[apache | nginx]：

Web服务器版本=> apache

要安装哪个PHP Server版本[5.4 | 5.5 | 5.6 | 7.0 | 7.1]：

PHP Server版本=> 7.1

你想要自动配置PHP [Y | n]：

自动配置PHP => y

您要安装哪个MariaDB Server版本[5.5 | 10.0 | 10.1]：

MariaDB Server版本=> 10.1

你想要+安装文件管理器[Y | n]：

文件管理器install => y

你想要+安装Zend优化加操作码缓存[Y | n]：

Zend操作码缓存install => y

你愿意+安装Memcached [Y | n]：

Memcached install => y
你想要+安装限制主机（限制CPU，RAM，IO您的主机帐户）[Y | n]：

限制主机install => y

你想配置内核限制DDOS [Y | n]：

内核限制DDOS => y

您想将VestaCP 8083端口更改为2083 [Y | n]：

将端口VestaCP 8083更改为2083 => y

你想要+安装Spamassassin＆Clamav [y | N]：

安装Spamassassin＆Clamav => n

你愿意+安装Fail2ban [y | N]：

安装Fail2ban => n

输入你的主机名[vdvesta.local]：

Hostname => vdvesta.local

输入您的邮箱[admin@vdvesta.local]：

Email => admin@vdvesta.local


#下面是原作者的介绍

VDVESTA
===================

VDVESTA is a small shell script auto Custom & Install VESTACP for your CentOS Server Release 7 x86_64.

VESTACP from: https://vestacp.com/#install
(Please buy Commercial Vesta's plugins if you can!)

----------

1/ VDVESTA System Requirements:
-------------
Install CentOS Server 7 x86_64: http://centos.org/

----------


2/ VDVESTA Install:
-------------
```
curl -L https://github.com/duy13/VDVESTA/raw/master/vdvesta.sh -o vdvesta.sh ; bash vdvesta.sh
```

vdvesta script interface:
-------------
```
        Welcome to VDVESTA:
A shell script auto Custom & Install VESTACP for your CentOS Server Release 7 x86_64.
                                                                Thanks you for using!

Would you like +install vDDoS Proxy Protection [Y|n]:
vDDoS Proxy Protection install => y
Which Web Server version you want to install [apache|nginx]:
Web Server version => apache
Which PHP Server version you want to install [5.4|5.5|5.6|7.0|7.1]:
PHP Server version => 7.1
Would you like auto config PHP [Y|n]:
Auto config PHP => y
Which MariaDB Server version you want to install [5.5|10.0|10.1]:
MariaDB Server version => 10.1
Would you like +install File Manager [Y|n]:
File Manager install => y
Would you like +install Zend optimize plus opcode cache [Y|n]:
Zend Opcode Cache install => y
Would you like +install Memcached [Y|n]:
Memcached install => y
Would you like +install Limit Hosting (limit CPU, RAM, IO your hosting account) [Y|n]:
Limit Hosting install => y
Would you like Configure Kernel limit DDOS [Y|n]:
Kernel limit DDOS => y
Would you like change port VestaCP 8083 to 2083 [Y|n]:
Change port VestaCP 8083 to 2083 => y
Would you like +install Spamassassin & Clamav [y|N]:
Install Spamassassin & Clamav => n
Would you like +install Fail2ban [y|N]:
Install Fail2ban => n
Enter your hostname [vdvesta.local]:
Hostname => vdvesta.local
Enter your Email [admin@vdvesta.local]:
Email => admin@vdvesta.local


 _|      _|  _|_|_|_|    _|_|_|  _|_|_|_|_|    _|_|
 _|      _|  _|        _|            _|      _|    _|
 _|      _|  _|_|_|      _|_|        _|      _|_|_|_|
   _|  _|    _|              _|      _|      _|    _|
     _|      _|_|_|_|  _|_|_|        _|      _|    _|

                                  Vesta Control Panel



Following software will be installed on your system:
   - Apache Web Server
   - Bind DNS Server
   - Exim mail server
   - Dovecot POP3/IMAP Server
   - MariaDB Database Server
   - Vsftpd FTP Server
   - Iptables Firewall


Would you like to continue [y/n]: y

......................................

Server version: Apache/2.4.16 (Unix)
mysql  Ver 15.1 Distrib 10.1.21-MariaDB, for Linux (x86_64) using readline 5.1
PHP 7.1.2 (cli) (built: Feb 15 2017 08:36:40) ( NTS )
Copyright (c) 1997-2017 The PHP Group
Zend Engine v3.1.0, Copyright (c) 1998-2017 Zend Technologies
    with Zend OPcache v7.1.2, Copyright (c) 1999-2017, by Zend Technologies

=====> Install and Config VDVESTA Done! <=====
 Link VestaCP: https://7.4.13.219:2083 or https://7.4.13.219:8083
        username: admin
        password: AYRZD32KAK

 Please reboot!

```

vdvesta screenshot:
-------------
![alt text](https://lh4.googleusercontent.com/-nS-2ZADtcpM/WK0GalcZfiI/AAAAAAAABI0/NELyFr6k-iMQkVEOGKylP55ibSDliu2gQCLcB/s1600/VDVESTA.png "Logo Title Text 1")

3. More Config:
---------------
Document: http://vdvesta.voduy.com
```
Still in beta, use at your own risk! It is provided without any warranty!
```
