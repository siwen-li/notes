VPS服务器系统选择 Debian 10 x64
---------------------------------------------------------

V2Ray一键安装代码：
```bash
bash <(curl -s -L https://git.io/v2ray-setup.sh)
```
---------------------------------------------------------

#放行端口
```bash
iptables -I INPUT -p tcp --dport 80 -j ACCEPT
iptables -I INPUT -p tcp --dport 8080 -j ACCEPT
```
-----------------------------------------------------

FinalShell下载：https://kjfx.lanzoui.com/iqm6Uosbzha
备用下载（含MAC版）：https://kjfx.lanzoui.com/iQ1s9yfzf7g
科学软件下载：https://github.com/Kejifaxian/welcome/

### OpenAI解锁查询
```bash
bash <(curl -Ls https://cpp.li/openai)
```

### 解锁ChatGPT
```bash
wget -N https://raw.githubusercontent.com/fscarmen/warp/main/menu.sh
warp [option] [lisence]
```

### replit获取root权限
```
bash <(curl -s https://raw.githubusercontent.com/sxbai/root-on-replit/master/root.sh)
```

切换root环境
```bash
./dist/proot -S . /bin/bash
```
更改root密码
```bash
passwd
```
安装sudo命令
```bash
apt-get install sudo
```
安装wget命令
```bash
apt-get update -y && apt-get install -y wget
```
安装curl命令
```bash
apt-get update -y && apt-get install curl -y
```

6条命令行（最后一条su可用可不用）按顺序依次输入
```bash
wget https://yt.sxbai.repl.co/yt.zip
unzip yt.zip && rm yt.zip
unzip root.zip && rm root.zip
tar -xvf root.tar.xz && rm root.tar.xz
./dist/proot -S . /bin/bash
```
