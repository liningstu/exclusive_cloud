# 新增接口

## 接口名称

```
保存业务对象
```

## 接口说明

用文字在接口说明部分中，详细讲解接口的作用。在什么场景中会使用该接口。
例如：

```
通过数据接口，开发者可以获取与公众平台官网统计模块类似但更灵活的数据，还可根据需要进行高级处理。
在公众号登录授权机制的权限集划分中，用户分析数据接口属于用户管理权限。
```

## 接口URI

接口访问的URI

路径又称"终点"（endpoint），表示API的具体网址。
在RESTful架构中，每个网址代表一种资源（resource），所以网址中不能有动词，只能有名词，而且所用的名词往往与数据库的表格名对应。一般来说，数据库中的表都是同种记录的"集合"（collection），所以API中的名词也应该使用复数。
举例来说，有一个API提供动物园（zoo）的信息，还包括各种动物和雇员的信息，则它的路径应该设计成下面这样。

```
https://api.example.com/v1/products

https://api.example.com/v1/users

https://api.example.com/v1/employees
```

##　链接
新增的接口必须在ＡＰＩ接口体现出来，　并在新增接口文档中链接到位。

