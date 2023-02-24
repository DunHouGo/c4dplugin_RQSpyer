# RQSpyer使用文档

### Cinema 4D渲染队列提示插件

<aside>
🔒 当前版本 ：1000

</aside>

# Download--下载

[BOGHMA 社区下载](https://community.boghma.com/)

[Gitee（国内源）](https://gitee.com/DunHouGo/c4dplugin_RQSpyer/repository/archive/master.zip)

[Github（国外源）](https://github.com/DunHouGo/c4dplugin_RQSpyer/archive/refs/heads/master.zip)

# Install--安装

- 推荐使用PluginManager统一管理安装更新：[PluginManager](https://www.notion.so/Plugin-Manager-72c5fe979541467187af2060fe330e80)
- 解压文件夹,复制到C4D的plugin文件夹下

> `%AppData%\Maxon\Maxon Cinema 4D R2x_xxxxxxxx\plugins\CINEMA 4D R2x\plugins\Boghma`
> 

<aside>
⚠️ 不要更改文件夹结构和名称，会导致插件报错

</aside>

# Intro--简介

- Cinema 4D 没有通知功能，对于经常需要渲染的使用者有些遗憾，RQSpyer顾名思义（Spy on Render Queue）提供后台对渲染队列状态的轮询，渲染全部结束时会向用户提供的邮箱发送提示邮件，避免猜测检查渲染是否完成的烦恼，趁着渲染，去喝杯茶吧🍵 !

# How to use--使用

1. 点击插件右上角“显示”图标，设置收件邮箱地址，点击保存
2. 争取设置并且勾选渲染队列
3. 开始检测

# Shortcut--快捷键

- No build-in shortcut

<aside>
⚠️ 如果停靠了面板，渲染之前点击右上角刷新按钮可以正确计算当前队列

</aside>