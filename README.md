# wei-harbor


### 安装教程

- wget https://mirror.ghproxy.com/https://github.com/goharbor/harbor/releases/download/v2.11.0/harbor-offline-installer-v2.11.0.tgz
- tar -xvf harbor-offline-installer-v2.11.0.tgz
- cp -ar harbor.yml.tmpl harbor.yml
- vim harbor.yml
````
hostname: xlai.cc  #这里配置的监听地址，也可以是域名
port: 10010 #这里配置监听端口
harbor_admin_password: yellow123!@#  # 配置admin用户的密码
data_volume: /root/data/harbor  #配置数据仓库
````
