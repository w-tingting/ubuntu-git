# Git在Ubuntu上的用法
- 安装
```
$ sudo apt-get install git
```
- Git配置
```
git config --global user.name "xxx"
git config --global user.email "邮箱地址"
```
- 创建公钥
```
ssh-keygen -C '邮箱地址' -trsa
```
- 上传公钥
  - 使用命令`cd ~/.ssh`进入`~/.ssh`文件夹；
  - 输入`gedit id_rsa.pub`打开`id_rsa.pub`文件，复制其中所有内容；
  - 在GitHub上加入SSH公钥
  
