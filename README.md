# CandyMieGame_PHP
一个用PHP做后端，js做控制器，H5做视图的卡牌堆叠小游戏。适用与竖屏手机！

# 开始运行(装载到服务器)

你需要再你的服务器中创建 Mysql 库 ，库的结构在 文件 [SQL.md](./SQL.md) 中。
并且在文件[index.php](./index.php)中填写入你访问数据库的账号与密码
```php
$sqlname = "";
$sqlpassword = "";
```
并且运行文件 [SQL.md](./SQL.md)中的命令。

# 添加关卡
需要在数据库 miegame 中表 level 中添加字段 代码如下：
```sql
INSERT INTO `level` (`id`, `address`, `level`, `trytasnum`, `tasnum`) VALUES ([第几关], [json存放路径], 4, 0, 0);
```

#  联系作者
有任何问题都可以联系作者：
QQ: 3325629928
E-mail: Mr_Xie_@outlook.com
GitHub: [https://github.com/MR-XieXuan](https://github.com/MR-XieXuan)
个人私站: [https://main.mrxie.xyz/](https://main.mrxie.xyz/)
CSDN: [https://blog.csdn.net/apple_53792700?spm=1011.2415.3001.5343](https://blog.csdn.net/apple_53792700?spm=1011.2415.3001.5343)
<br/>
&emsp;如果本代码对您有帮助的话，可以给本代码一个Star或者是Fork本代码。你的每一个fstar可以给作者非常大的鼓励。
&emsp;如果遇到困难，欢迎联系作者，你可以私聊作者或者添加作者QQ、发送电子邮件向作者寻求帮助。也可以在Issue向大家提问。
