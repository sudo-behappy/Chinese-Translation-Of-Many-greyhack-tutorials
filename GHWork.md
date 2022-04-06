

# 黑客指南(v0.7.4) [原帖](https://steamcommunity.com/sharedfiles/filedetails/?id=1905138308)

关于破解系统, 游戏基础, 提示和游戏小技巧的指南

## 老工具

sshcrack, sshguest, shellmail, sshnuke, shellweb, sshescale, ftpnuke, web3xploit 这些先前的工具已经被**移除**. 你需要使用新的工具, 或者自己写你自己的工具

***

## 你将要需要的工具

### 预装工具:

- **whois**: 你可以用这个来获取一个服务器拥有者的联系方式和其他信息
- **nslookup**: 获取一个域名的IP地址
- **scanlan.exe**: 查看你所连接的网络下的其他设备
- **ssh**: 通过远程机器的用户名和密码来链接远程主机的ssh服务
- **ftp**: 通过远程机器的用户名和密码来链接远程主机的ftp服务
- **logviewer**: 查看和清除电脑的log
- **ping**: 检查远程主机是否可以连接

### 普通商店的工具
- **nmap**: 获取特定IP的开放端口情况
- **smtp-user-list**: 获取特定IP在SMTP服务器
- **ConfigLan**: 用来管理你租的服务器或者配置网络

### 黑客商店的工具
- **AdminMonitor.exe**: 当管理员上线和开始主动追踪你的时候发出警告. 以防万一, 尽量一直在后台挂着.
- **decipher**: 用来破解密码
- **scanlib**: 如果你不想写你自己的破解工具, 不要下载(分析一个库(library), 展示该库的弱点 -- 译者注)
- **scanrouter**: 用来扫描kernal_router.so库. 必要
- **metaxploit.so**: 所有的**破解**都需要这个库, 让它保持在最新版本.
- **crypto.so**: 所有的**解密**都需要这个库, 让它保持在最新版本.
- **Sniffer**: 在路由器上运行并等待, 可以截获密码
- **rshell-server** 和 **rshell-interface**: 你需要在你租的服务器上安装rshell-server来运行rshell-interface(自己的服务器也可以, 但不建议这样做, 会留漏洞 --译者注). 这两个工具能够在你和你的受害者之间建立连接, 然后你就可以为所欲为. 这个需要配合社工使用, 参见社工部分
- 如果你不知道在**exploits**下你需要什么, 点开在右边的服务列表并好好读读(在上面的select library下拉菜单中 -- 译者注)