# 安装
## 跳过git的安装步骤，进入设置步骤
### 1.在安装完后设置用户名和用户邮箱
![image](..)
### 2.本地化仓库
![image](..)
### 3.添加ssh
#### 3.1生成SSH
    $ ssh-keygen -t rsa -C "XXXX@XXX.com" 
![image](..)
#### 3.2 验证是否生成成功
    $ ls  
#### 3.3 粘贴SSH秘钥
    $ cat id_rsa.pub 
#### 3.4 粘贴以 ssh_rsa开头的秘钥，并在GitHub的setting页面上点击SSH and GPG key，添加新的SSH即可
### 4.验证和修改
#### 4.1测试是否成功配置
$ ssh -T git@github.com 

Hi [Your user name]! You've successfully authenticated, but GitHub does not provide shell access.