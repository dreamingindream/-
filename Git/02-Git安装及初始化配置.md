### 安装 

官网自己搞定


### 初始化配置

写自己的名字和邮箱
```
git config --global user.name 'your_name';
git config --global user.email 'your_email';
```

#### `config` 的三个作用域

`local`：对某个仓库有效

`global`：对当前用户所有仓库有效

`system`：对系统所有登录用户对所有仓库有效

查看当前的 Git 配置
```
git config --list [--local, --global, --system]
```

