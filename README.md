# 备忘录
## Centos7防火墙相关命令
#### 查看防火墙规则
` firewall-cmd --list-all `
####  查询666端口是否开放
` firewall-cmd --query-port=666/tcp `
 #### 开放666端口
` firewall-cmd --permanent --add-port=666/tcp `
 #### 关闭666端口
` firewall-cmd --permanent --remove-port=666/tcp `
#### 查看防火墙开放的端口 
` firewall-cmd --permanent --list-ports `
#### 重启防火墙(修改配置后需重启)
` firewall-cmd --reload `
