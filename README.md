# fis3-arrow

基于fis3+Velocity的前端解决方案

* commonjs规范
* sass预处理器
* 支持跨模块处理

## Features
* 扩展自 fis3，包含 fis3 的所有提供功能以及 fis 的插件都可使用
* Smarty 模板压缩
* XSS 自动转义
* 内置 less 解析插件，使用 less 无需任何设置
* 内置 baiduTemplate 解析插件
* 指定 目录规范，建议遵循此目录规范；
* 内置脚手架，执行 fisp init -h 命令可查看详细信息
* 内置 .po 文件解析成 .json 的插件，方便国际化支持
* 本地环境模拟套件，使用命令 fisp server init 安装，提供 Smarty 模板的解析，数据模拟，以及 URL 转发功能；
* components 支持
* fis-preprocessor-components
* fis-command-install

## Install
1. install nodejs, 建议fis3支持的版本
2. install