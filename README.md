![](https://s2.loli.net/2022/07/12/YvMDmqbVdLRWzCl.png)
# Croe
![GitHub release (latest by date)](https://img.shields.io/github/v/release/WuoLun/Croe)
![](https://img.shields.io/github/stars/WuoLun/Croe)
[![GitHub license](https://img.shields.io/github/license/WuoLun/Croe)](https://github.com/WuoLun/Croe/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/WuoLun/Croe)](https://github.com/WuoLun/Croe/issues)
![](https://img.shields.io/badge/author-Charles-blue)

Croe是一个开源的匿名信项目，通过一些匿名信件，来达到秘密传输心意的想法
## 优势
- 🗯官方询问支持
- 🔨高的可开发度
- 🔰支持AJAX
- 🔰支持数据库（Only 2.0.x）
- ❇️官方JSON数据库支持
- 🤭更多正在开发！

# 安装
推荐配置：
- PHP 7.0以上
- 服务器运存>=1GB

下载最新发行版安装包，解压至服务器目录

## 配置邮箱
邮件发送基于PHPMailer

文件`Server/send.php`为邮箱配置文件，配置说明：
```php
$smtp="";//smtp地址
$name="Croe匿名信件";//发信时显示的用户名
$email="";//设置发件人邮箱地址 同登录账号
$password="";//密码，或授权码
$from="";//同登录账号
$reply="";//回复时回复到哪个邮箱
$subject="";//邮件主题
```
**无需复制粘贴，配置文件有**

# API
可前往[官方Wiki站](https://wiki.x-turbo.top/croe/#/API)查看接口

# 开发
使用Croe开发是很容易的，官方Wiki站提供了很多开发案例，你可以[前往查看](https://wiki.x-turbo.top/croe)
### 帮助
你可提交issues，我们会在48小时内查看并回复！

