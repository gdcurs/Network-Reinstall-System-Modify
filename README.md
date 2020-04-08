# Network-Reinstall-System-Modify
It can reinstall CentOS, Debian, Ubuntu, Windows 2003, 7, 2008R2, 2012R2, 2016, 2019 and other systems (continuously added) via the Internet, and can install any system via mounting remote network ISO.

[One-click Network Reinstall System – Magic Modify version](https://tech.cxthhhhh.com/linux/2018/11/27/original-one-click-network-reinstall-system-magic-modify-version-for-linux-windows-en.html), Forked from [MoeClub Vicer](https://moeclub.org/2018/04/03/603/), technical support and maintenance provided by [Technical Blog | 技術博客](https://tech.cxthhhhh.com/), more features of the magic version are constantly increasing.

##

1.下载SHELL脚本（通过root用户运行）
wget –no-check-certificate https://raw.githubusercontent.com/MeowLove/Network-Reinstall-System-Modify/master/Network-Reinstall-System-Modify.sh && chmod a+x Network-Reinstall-System-Modify.sh

2.装系统（任选其一）
【安装Linux系统】

①. 一键网络重装纯净 CentOS 8（推荐）

bash Network-Reinstall-System-Modify.sh -CentOS_8
②. 一键网络重装纯净CentOS 7

bash Network-Reinstall-System-Modify.sh -CentOS_7
③. 一键网络重装纯净CentOS 6

bash Network-Reinstall-System-Modify.sh -CentOS_6
④. 一键网络重装纯净Debian 9（推荐）

bash Network-Reinstall-System-Modify.sh -Debian_9
⑤. 一键网络重装纯净Debian 8

bash Network-Reinstall-System-Modify.sh -Debian_8
⑥. 一键网络重装纯净Debian 7

bash Network-Reinstall-System-Modify.sh -Debian_7
⑦. 一键网络重装纯净Ubuntu 18.04（推荐）

bash Network-Reinstall-System-Modify.sh -Ubuntu_18.04
⑧. 一键网络重装纯净Ubuntu 16.04

bash Network-Reinstall-System-Modify.sh -Ubuntu_16.04
⑨. 一键网络重装纯净Ubuntu 14.04

bash Network-Reinstall-System-Modify.sh -Ubuntu_14.04
【安装Windows系统】

*警告：你需要购买来自Microsoft或其合作伙伴正版系统授权并激活系统使用。继续安装即代表您知悉并已经购买正版授权。

①. 一键网络重装纯净Windows Server 2019（推荐）

bash Network-Reinstall-System-Modify.sh -Windows_Server_2019
②. 一键网络重装纯净Windows Server 2016

bash Network-Reinstall-System-Modify.sh -Windows_Server_2016
③. 一键网络重装纯净Windows Server 2012 R2

bash Network-Reinstall-System-Modify.sh -Windows_Server_2012R2
④. 一键网络重装纯净Windows Server 2008 R2

bash Network-Reinstall-System-Modify.sh -Windows_Server_2008R2
⑤. 一键网络重装纯净Windows 7

bash Network-Reinstall-System-Modify.sh -Windows_7_Vienna
⑥. 一键网络重装纯净Windows Server 2003

bash Network-Reinstall-System-Modify.sh -Windows_Server_2003
【安装DD系统】

*如果您不了解这意味着什么，请不要进行操作。%ULR%应该替换为您自己的映像地址。

bash Network-Reinstall-System-Modify.sh -DD “%URL%”
恭喜，你已经完成了系统重装，享受当下的美好
当您执行完上面的2行命令，你的服务器将开始网络重装纯净系统。在完成安装前，您将无法进行连接管理。

因硬件配置和网络环境不同，安装全程需要15-60分钟，请耐心等待。安装完成即可通过IP:22(Linux SSH)/IP:3389(Windows RDP)进行连接。

## Realistic Demand
Why do we need to reinstall a pure system?

1. The system template provided by the service provider may have some built-in software, even conflicting with the software we are about to install, resulting in the installation failure.

2. ISO mount is not a service provided by all service providers. Some IPIM/KVM transmission speeds are too slow and installation efficiency is poor.

3. Linux/Windows may encounter some inexplicable errors that cannot be found in use. I believe you must have a deep understanding!


## You Need To Understand
Where are the release notes and tutorials?

1. If you are from an English community, please click here.  
https://tech.cxthhhhh.com/linux/2018/11/27/original-one-click-network-reinstall-system-magic-modify-version-for-linux-windows-en.html

2. 如果你来自于中文社区，请点击这里。  
https://tech.cxthhhhh.com/linux/2018/11/29/original-one-click-network-reinstall-system-magic-modify-version-for-linux-windows-cn.html


## Common Problem
Here and the tutorials in my blog will cover the answers to most questions.

1. Q：The default password for the system installation?  
A：The default password for all system installations is [cxthhhhh.com]. To prevent brute force cracking, you must change the default password immediately after installation!

2. Q：How to connect and control my new system？  
A：Due to different hardware configuration and network environment, the installation takes 15 to 60 minutes, please be patient. Once the installation is complete, you can connect via IP: 22 (Linux SSH) / IP: 3389 (Windows RDP).

3. Q：How to manually install any system using [Bare-metal_System_Deployment_Platform]?  
A：It's hard to describe the process in one sentence, so visit my blog and follow the tutorial.

4. Q：Why isn't the content of the project stored on Github not all?  
A：As we all know, Github can only upload files smaller than 100MB. However, as of January 1, 2019, all files in the entire Network-Reinstall-System-Modify project totaled more than 50GB. So I can only upload script content and smaller files, including various image files and the auxiliary platform I built will not be able to upload. But you can visit [Open Disk CDN](https://opendisk.cxthhhhh.com/) to learn more.

5. Q：How to communicate? Feedback question?[Support language English (Recommended), Chinese (中文).]  
A：You can join my Telegram channel and discussion groups for instant communication and feedback. You can also submit an Issues, but this is not immediate, but it is easy to track.  
[Telegram Channel：My Share](https://t.me/me_share)  
[Telegram Chat Group：Technical Blog | 技術博客](https://t.me/Technical_Blog)


## End Notes
[Network-Reinstall-System-Modify](https://tech.cxthhhhh.com/linux/2018/11/27/original-one-click-network-reinstall-system-magic-modify-version-for-linux-windows-en.html)

Version：V2.0.3  
Date：2019/01/06

[Technical Blog | 技術博客](https://tech.cxthhhhh.com/)  
https://tech.cxthhhhh.com/
