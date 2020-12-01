### 更新日志 11-30

新增 uniCloud 云开发，小程序数据可通过 api 更改。
（如只需要数据写死在前端，可切换到静态数据分支 [no-api](https://github.com/zwpro/coupons/tree/no-api)）

# 美团饿了吗 CPS 红包，别人领红包下单，你拿推广佣金

<img src="https://raw.githubusercontent.com/zwpro/coupons/master/static/demo.png" width="300"/>

### 使用方法

源码为 uniapp 项目，需下载 hbuilder 导入项目打包，可编译成 h5 或小程序(跳转地址为小程序路径)

### 常见问题

1. 如何获取美团饿了吗的推广链接

美团联盟：https://union.meituan.com/

饿了么、双十一：https://pub.alimama.com/

​ 2.如何打包成小程序

编译成小程序的话，需要配置 coupons 里小程序路径

比如跳转饿了么小程序：

```
minapp: {
    appid: 'wxece3a9a4c82f58c9',
    path: 'pages/sharePid/web/index?scene=https://s.click.ele.me/wR9ecuu'
}
```
