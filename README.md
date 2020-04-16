# Linux-NetSpeed

安装
```
wget -N "https://raw.githubusercontent.com/ss-daily-backup-002/Linux-NetSpeed-cx9208/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
不要随便在生产环境使用，生产环境建议手动安装   

# 验证证书版

解决证书问题
```
# Debian
apt-get install ca-certificates -y
# CentOS
yum install ca-certificates -y
```
安装
```
wget -N "https://raw.githubusercontent.com/ss-daily-backup-002/Linux-NetSpeed-cx9208/master/tcp-check-cert.sh"
chmod +x tcp-check-cert.sh
./tcp-check-cert.sh
```

