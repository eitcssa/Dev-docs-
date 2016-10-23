## Dev-docs-
开发文档

### 环境设置

### 远程登录服务器：
ssh ubuntu@107.191.52.183 -p 52222
or ssh ubuntu@eitcssa.eu -p 52222

ubuntu密码:ubuntu  
root权限: azxohguyc!8  
MySQL root password: ubuntu

### MediaWiki 管理员账户
username: eitcssa  
PW: eitcssa16

### 服务器文件编辑
可以通过`sftp`将服务器上文件下载到本地进行编辑，之后上传回服务器替换原文件。  
对于没有写文件权限的路径，可以先将文件上传至`/home/ubuntu/`目录下，之后用`sudo`移动文件到相应路径。  
sftp GUI软件: FileZilla

### TODO list 
- [x] 安装MediaWiki https://help.ubuntu.com/community/MediaWiki
- [ ] 将域名 wiki.eitcssa.com 挂在DNS上 (com ?)
  - [ ] 确定二级域名及其他URL
  - [x] 将URL `http://107.191.52.183/mediawiki/` 中IP改为域名eitcssa.eu

### MediaWiki
- extensions: 1. ImageMap (https://www.mediawiki.org/wiki/Extension:ImageMap#Composer)
              2. 富文本编辑器 ()
- version: 1.19 (eitcssa.eu/wiki/index.php?title=Special:Version)

