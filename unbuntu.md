




<h1>一键安装unbutu系统
</h1>
【Note: 命令依次执行，如果失败请重试，过程时间有点长，请耐心哦】
====================================
文章链接： https://www.qiushaocloud.top/2021/12/25/termux-install-ubuntu
apt update
# apt upgrade -y 如果遇到需要确认的，请确认下，博主这边全部 enter
apt upgrade -y
pkg update
pkg upgrade -y
pkg install wget vim proot -y
pkg install proot-distro -y
# 显示受支持的发行版
proot-distro list
# 博主选择安装 ubuntu
proot-distro install ubuntu
echo "proot-distro login ubuntu" > join-ubuntu.sh
chmod 777 join-ubuntu.sh







<h1>一键安装unbutu图形化系统
（下载vnc viewer 127.0.0.1:5901）
</h1>
第一步：打开Termux输入下面这条命令：

bash -c "$(curl -L gitee.com/djyd/termux-ubuntu2004/raw/main/ubuntu20)"

【b站视频教程】 b23.tv/QqLeVam

第二步：安装过程约30分钟左右不止，看你手机（平板）性能。免Root。

第三步：安装完成，提示你退出Termux，结束一下Termux运行，重新打开。

第四步：打开Termux直接回车进入ubuntu20.04，请使用Vnc或其他你过的图形连接软件。









