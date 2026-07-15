## 命令

### 登录：

mysql -u root -p

输入密码

### 查看所有账户：

 SELECT User, Host FROM mysql.user

### 修改密码：

ALTER USER 'luyao'@'%' IDENTIFIED BY 'Luyao@2025!';