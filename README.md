**finalshell备份**

激活

机器码获取
随便输入账号密码，然后选择离线激活即可获得机器码。

防止二次打开提示激活

Windows下hosts文件位置

windows 用户hosts文件是在“c:\windows\system32\drivers\etc，注意这个文件一定是在系统盘，如果你的系统在D盘请自行修改前面的盘符

快速进入hosts文件夹的方法。同时按下Win+R组合键，调出运行栏，输入 c:\windows\system32\drivers\etc 点击确定就可以找到hosts文件了。

修改本机hosts文件，将下面地址指向127.0.0.1

127.0.0.1 www.youtusoft.com
127.0.0.1 youtusoft.com
127.0.0.1 hostbuf.com
127.0.0.1 www.hostbuf.com
127.0.0.1 dkys.org
127.0.0.1 tcpspeed.com
127.0.0.1 www.wn1998.com
127.0.0.1 wn1998.com
127.0.0.1 pwlt.wn1998.com
127.0.0.1 backup.www.hostbuf.com

然后使用cmd或者Windows终端执行以下命令查看hosts是否生效

ping dkys.org
返回地址127.0.0.1即可
