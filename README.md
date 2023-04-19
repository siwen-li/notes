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
```bash
wget https://github.com/techcode1001/replit_root/releases/download/v1.0/yt.zip

unzip yt.zip

unzip root.zip

tar -xvf root.tar.xz

./dist/proot -S . /bin/bash
```

安装curl命令
```bash
apt-get update -y && apt-get install curl -y
```
安装wget命令
```bash
apt-get update -y && apt-get install -y wget
```

---------------------------------------------------------
apt update -y
apt install -y curl socat

X-UI 安装代码：
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)

#放行端口
iptables -I INPUT -p tcp --dport 443 -j ACCEPT
iptables -I INPUT -p tcp --dport 54321 -j ACCEPT

#申请 SSL 的证书
输入命令：x-ui

# x-ui 管理面板设置
添加证书和密钥路径，重启面板
通过域名访问x-ui 管理面板：https://域名:54321
