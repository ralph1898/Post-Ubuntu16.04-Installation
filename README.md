# Post-Ubuntu16.04-Installation

小写为代码直接安装，大写为要看教程安装

Ubuntu 16.04 一系列软件安装命令，包括QQ、搜狗、Chrome、vlc、网易云音乐安装方法 (http://blog.csdn.net/fuchaosz/article/details/51882935)

sudo apt-get update

unity tweak tool (via software center)

gdebi (这样就能 sudo gdebi ANY-DEB-FILE)

Dropbox (dropbox.com) & Mega (mega.co.nz)

Foxit Reader

Wechat (https://github.com/geeeeeeeeek/electronic-wechat https://fusion809.github.io/howto-install-nodejs/)

Bcloud (https://www.zhihu.com/question/51266530)

aria2 & uget

terminator

Powerline (https://github.com/b-ryan/powerline-shell need to change the path from /bash/ into /bindings/bash/)

p7zip & unrar & mcomix

Peazip (https://www.linuxbabe.com/ubuntu/install-peazip-ubuntu-16-04)

五笔输入法 (http://www.pinyinjoe.com/linux/ubuntu-12-chinese-setup.htm)

Sublime Text 3 (https://www.simonewebdesign.it/how-to-install-sublime-text-3-on-debian/ & http://appnee.com/sublime-text-3-universal-license-keys-collection-for-win-mac-linux/ , http://askubuntu.com/questions/396938/how-do-i-make-sublime-text-3-the-default-text-editor)

GET Root Permission on GUI operation (Press Alt + F2 to run a command and then enter "gksu nautilus" (using gksu is the recommended way to open GUI's with root permissions). There's a nautilus script that allows you to open a directory as root, look for nautilus-gksu on your repositories.)

vlc smplayer

gimp shutter

vivaldi, pepperflashplugin-nonfree (sudo apt install pepperflashplugin-nonfree https://vivaldi.net/en-US/forum/vivaldi-browser-for-linux/13425-a-way-to-install-pepperflash-in-ubuntu), chromium-codecs-ffmpeg-extra (播MP4 online) (sudo apt-get install chromium-codecs-ffmpeg-extra http://www.webupd8.org/2016/04/how-to-get-flash-and-h264-to-work-in.html https://www.youtube.com/html5)

安装flash player on firefox (http://blog.csdn.net/wangyuchun_799/article/details/46995675, alt + F2, 然后输入 gksu nautilus, 可以实现GUI自由复制粘贴文件夹)

flashplugin-installer (sudo apt-get install flashplugin-installer)

texlive (sudo apt-get install texlive-full) & texstudio

Youdao词典 (安装deepin版本即可 youdao-dict_1.1.0-0-deepin_amd64.deb)

Wine (http://www.itdadao.com/articles/c15a363861p0.html)

Adobe Reader (http://askubuntu.com/questions/767937/how-to-install-adobe-acrobat-in-ubuntu-16-04)

lm-sensors curl hddtemp conky conky-all (http://www.tecmint.com/install-conky-in-ubuntu-debian-fedora/, Set "own_window_type" in the config to "override", background = true. https://linux.cn/article-5474-1.html)

爱壁纸 & Python-support 1.0.15 (https://launchpad.net/ubuntu/xenial/amd64/python-support/1.0.15, http://www.lovebizhi.com/linux.html)

xrx7855.ppd (http://www.cornellcollege.edu/information-technology/get-connected/printing-2016/eprint-driver-install.shtml)

Franz (Linux下聊天集成平台) (https://gist.github.com/jamiesoncj/756728b3ba7c07d7a90f843400af37bb)

SNES模拟器 (http://www.linuxandubuntu.com/home/how-to-play-your-childhood-nintendo-games-in-linux)

打印机 Brother HL-L2380DW (http://support.brother.com/g/b/downloadhowto.aspx?c=us&lang=en&prod=hll2380dw_us_as&os=128&dlid=dlf006893_000&flang=4&type3=625)

    Download LPR driver.
    Login as a superuser (or use "sudo" option if required).
    
    Check if pre-required procedures are completed
    For Ubuntu
    For Distributions using firewall
    GIMP is required for "scan-to-image"
    brscanX should be installed first
    
    Install the driver.
    Open the terminal and go to the directory where the driver is. 
    Install the scan-key-tool.
    Command  :  dpkg -i  --force-all  (scan-key-tool filename)
    Check if the scanner driver is installed.
    Command  :  dpkg -l  |  grep  Brother
    
    Run scan-key-tool and try the test scanning.
    Run scan-key-tool(The program will run as a background process.)  
    Command  :  brscan-skey 
    Check if the scan-key-tool detect your scanner device.
    Command  :  brscan-skey -l
    Press the scan button, select user, select destination, press START.
    

虚拟打印机 cups-pdf (sudo apt-get install cups-pdf 和 sudo chmod 4755 /usr/lib/cups/backend/cups-pdf 和 sudo chmod 700 /usr/lib/cups/backend/cups-pdf 和 sudo chmod 700 /usr/lib/cups/backend/，文件在～/PDF文件夹内)

USB音响 (要调alsamixter，要选digital output，http://www.linuxquestions.org/questions/linux-software-2/usb-speakers-as-default-649705/#post3187306, http://askubuntu.com/questions/523959/how-to-fix-very-low-sound-in-xubuntu-14-04)

Dukto R6 不同操作系统互传文件 (http://www.msec.it/blog/?page_id=11)

PDFSam

小小五笔输入法 (http://yong.dgod.net/)

