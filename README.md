## 五念技术部中高级PHP程序员测试题

    下面测试任选其一，完成之后可以用你的github或bitbucket仓库分享给我们(尤佳)，或把代码及数据库发送到maggiezh@wuniansy.com。

### TEST 1
---
#### 描述

    - 使用移动开发技术结合你熟悉的后端框架做一个前后端分离的移动应用demo
    - 简单的登陆注册忘记密码以及用户基本信息展示页面即可。
    - 最后的apk文件和IPA文件能够安装到手机上。

    * 要求使用API Cloud（+分）
    * 要求使用PHP+Apache/Nginx+MySql(版本不限)
    * 框架要求TP3.2, TP5.0,<b>不可以使用cms</b>

#### 文档链接

- [API Cloud](http://www.apicloud.com/)
- [TP5.0手册](https://www.kancloud.cn/manual/thinkphp5)
- [TP3.2手册](https://www.kancloud.cn/manual/thinkphp/1678)


### TEST 2
---
#### 内容描述

    - 使用你熟悉的框架做一个简单的线上交易商城以及后台。
    - 会员用户登录后可以购买商品->订单预览(修改商品数量)->订单确认->支付(可以不用做通)。
    - 会员用户登录后可以查看管理员发布的文章（公告）并且评论，其他用户之间可以相互评论。
    - 后台管理员可以在后台查看并且管理商品，修改添加的时候并且可以批量上传商品图片。
    - 后台管理员可以在后台查看并且管理(CURD)所有用户，可以修改用户的状态status。
    - 后台管理员可以在发布文章以及管理评论。

    * 要求使用PHP+Apache/Nginx+MySql(版本不限)
    * 框架要求TP3.2, TP5.0，<b>不可以使用cms</b>
    * 合理设计数据库
    * 前端界面干净整洁即可

#### 文档链接

- [TP5.0手册](https://www.kancloud.cn/manual/thinkphp5)
- [TP3.2手册](https://www.kancloud.cn/manual/thinkphp/1678)

### TEST 3
---
#### 内容描述

    - 使用<b>Laravel5.4</b>框架完成以下需求
    - 创建用户模块，并使用Laravel Auth完成用户登录，注册，找回密码，资料修改及上传头像。
    - 创建文章模块以及评论，该模块要实现文章的增删（只有作者和管理员可以删除）改查以及评论的无限极分类。
    - 后台管理员(可以指定一个账号)，对用户、文章及评论进行CURD。
    - 整个项目使用RESTful风格基于资源路由以及资源控制器完成。

    * 要求使用PHP+Apache/Nginx+MySql(版本不限)
    * 框架要求Laravel，<b>不可以使用cms</b>
    * 合理设计数据库，使用migration做脚本迁移
    * 完整的说明文档README.md
    * 注意gitignore
    * 前端界面干净整洁即可

#### 文档链接

- [laravel官网](https://laravel.com/)
- [laravel服务 - 用户认证](http://laravelacademy.org/post/3074.html)
- [laravel HTTP控制器实例教程 - 创建RESTFul风格控制器实现文章增删改查](http://laravelacademy.org/post/549.html)
