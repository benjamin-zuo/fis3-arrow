# fis3-arrow
基于fis3+Velocity的前端解决方案

## 特性及优势
* 扩展自 fis3，包含 fis(3) 的所有提供功能以及 fis(3) 的插件都可使用
* 基于 velocity 模板，前后端分离
* 内置 sass 解析插件，使用 sass 无需再设置
* 内置 utc 前端模板解析插件
* 指定目录规范
* 内置脚手架 fis3-arrow-scaffold 
* 提供后端数据模拟及 URL 转发功能
* 公共组件库模块可抽离
* 单模块更新与发布
* 跨模块调用静态资源和VM模板
* 共享UI组件库及通用业务模块
* UI组件库更新CDN单独发布

## 安装
1.安装nodejs
Node 版本要求 0.8.x，0.10.x, 0.12.x，4.x，6.x，不在此列表中的版本不予支持。下载[nodejs](http://www.nodejs.org/)
2.安装fis3-arrow
```
sudo npm install fis3-arrow -g --registry=https://registry.npm.taobao.org
```
安装完之后执行看是否安装成功
```
fisa -v
```
3.安装脚手架
```
sudo mkdir project
cd project
fis3 init fis3-arrow-scaffold
```

## 编译
```
cd project
fisa release -r home
fisa release -r common
```

## 发布
```
// 发布到生成环境
fisa release prod
// 发布到rd环境
fisa release rd
// 发布到指定output目录
fisa release -d ../output
```

## 预览
```
fisa server start
// 指定8090端口
fisa server start -p 8090
```
