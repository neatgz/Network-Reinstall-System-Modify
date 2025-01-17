# Network-Reinstall-System-Modify
It can reinstall CentOS, Debian, Ubuntu, Windows 2003, 7, 2008R2, 2012R2, 2016, 2019 and other systems (continuously added) via the Internet, and can install any system via mounting remote network ISO.

[One-click Network Reinstall System – Magic Modify version](https://tech.cxthhhhh.com/linux/2018/11/27/original-one-click-network-reinstall-system-magic-modify-version-for-linux-windows-en.html), Forked from [MoeClub Vicer](https://moeclub.org/2018/04/03/603/), technical support and maintenance provided by [Technical Blog | 技術博客](https://tech.cxthhhhh.com/), more features of the magic version are constantly increasing.

# Usage
http://rsnote.com/60.html

apt install -y xz-utils openssl gawk file

wget --no-check-certificate -qO ~/Network-Reinstall-System-Modify.sh 'https://github.com/neatgz/Network-Reinstall-System-Modify/raw/master/Network-Reinstall-System-Modify.sh' && chmod a+x ~/Network-Reinstall-System-Modify.sh

bash ~/Network-Reinstall-System-Modify.sh -CXT_Bare-metal_System_Deployment_Platform

VNC
1、请进入 [选项 0] 或者 [选项 1]，进行手动安装系统。
2、选择 [Linux Installs] 选项。我们将在下一步中，选择要安装的系统。
3、选择 [Installer] 或者 [Graphical Installer] 选项，启动图形化系统安装界面。
4、最后就按照手动安装 Linux 系统的步骤自行解决即可！

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
