# 安装
需求
--------------------------------

* PHP5.6 版本或以上

* 目前仅支持连接mysql数据库。


## 安装

推荐使用composer进行安装Devhay。composer是PHP的依赖管理工具，允许你在项目中声明依赖关系，并安装这些依赖。

> 关于composer的安装，配置和使用方法见 http://docs.phpcomposer.com/

首先在composer.json文件中添加devhay的资源库地址

```javascript
"repositories": [
  {
      "type": "vcs",
      "url": "git@code.aliyun.com:devhay/lib.git"
  }
]
```

然后作为依赖增加到你的项目中

```shell
composer require devhay/lib
```

安装完毕之后，在你的项目中引入composer自动加载文件即可。例如：

```php
require vendor/autoload.php
```



## 开发版

要使用开发版本，只需要添加版本号 **@dev** 即可

```powershell
composer require devhay/lib @dev --dev
```

