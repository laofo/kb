

# 前提条件
目前，CentOS 仅发行版本中的内核支持 Docker。
Docker 运行在 CentOS 7 上，要求系统为64位、系统内核版本为 3.10 以上。
查看内核版本命令
```
uname -r
```

# 安装 Docker

- yum 直接安装
  ```
  yum -y install docker-io
  ```
  
- rpm 包安装
  ```
    yum install -y policycoreutils-python
    yum install -y yum-plugin-ovl
    yum install -y docker-ce-18.06.0.ce-3.el7.x86_64.rpm

  ```
# 启动 Docker
```
service docker start
```
