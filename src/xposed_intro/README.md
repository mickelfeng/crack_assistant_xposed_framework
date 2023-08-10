# Xposed简介

* `XPosed`
  * 是什么：本身是一个框架
    * 所以也称：`XPosed框架`
      * =`Xposed Framework`
  * 适用对象：安卓手机
  * 作用：可以在XPosed中安装各种插件，实现各种高级功能
    * 引申：常被用来配合破解安卓应用
  * 前提：需要安卓手机有`root权限`
  * 特点
    * 开源
    * 支持插件
      * 安装插件后，可以实现各种原本很难实现的效果

## Xposed发展历史=各种版本

* Xposed发展历史=各种版本
  * 最早：`Xposed` = `旧版Xposed` = `OG Xposed`
    * 支持Android版本：`Android 2.3` ~ `Android 8.1`
  * 后来：`EdXposed`
    * 支持Android版本：`Android 8.0` ~ `Android 11`
      * 已停止维护，不再支持`安卓11+`的版本
    * 主页
      * https://edxp.meowcat.org
    * Github
      * EdXposed
        * https://github.com/ElderDrivers/EdXposed
          * A Riru module trying to provide an ART hooking framework (initially for Android Pie) which delivers consistent APIs with the OG Xposed, leveraging YAHFA (or SandHook) hooking framework, supports Android `8.0 ~ 11`
      * EdXposedManager
        * https://github.com/ElderDrivers/EdXposedManager
  * 最新：`LSPosed`
    * 支持Android版本：`Android 8.1` ~ `Android 13`
      * 支持最新的`Android 13`
    * Github
      * https://github.com/LSPosed/LSPosed
        * A Riru / Zygisk module trying to provide an ART hooking framework which delivers consistent APIs with the OG Xposed, leveraging LSPlant hooking framework
