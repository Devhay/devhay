# 快速入门

> 如果你未安装Devhay，请先进入 [安装](install.html)。

要在你的项目中使用Devhay进行开发，首先你的项目文件结构需要符合以下规范：

```reStructuredText
|-- app  #模块目录
|   |-- page  #默认模块目录 ( 可选 )
|   |   |-- template #当前模块的视图目录
|   |   |-- controller.php #当前模块的控制类 (必须)
|   |   `-- action.php #当前模块的行为类 (可选)
|   `-- ...   更多模块目录
`-- vendor/devhay/lib
```

