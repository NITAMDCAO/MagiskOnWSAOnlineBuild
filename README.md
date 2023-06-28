# [点击下载最新版本](https://github.com/yige-yigeren/MagiskOnWSAAuto/releases/latest)

本项目基于临时克隆MagiskOnWSA，并直接调用build.sh来创建最新版本并发布于Releases。

默认设置：

每两周运行一次。build参数：稳定版stable；有root权限Root Magisk；带Google Play；移除Amazon store。

## 如果要自己构建

请不要直接fork仓库，自己创建仓库后将Build.yml填入即可。

必需私有变量：[PUBLISH_TOKEN](https://github.com/settings/tokens)，用于访问github并发布，请给予仓库相关权限。

相关仓库地址什么的改成自己的。

## 运行

提前预填好build.sh的参数，跳过run.sh直接执行（需要修改参数请run.sh里获取），使用Github Releases发布。

至于有什么更好的发布的方法也可以，也欢迎提出建议。

## 免责声明

本仓库仅以公开的方式自动构建Magisk On 适用于 Android™️ 的 Windows 子系统，不提供对于构建正常、软件能正常运行的保证，不保证您数据的安全性与可靠性。

由于MagiskOnWSA仍然处于更新中，其Build参数可能会变化，本仓库不一定能及时更改，请在安装使用前确保相应参数与你的要求相匹配。
        
不对错误的Build造成的数据损坏与丢失负任何责任。
        
我不会收集任何数据，仅以原样提供构建。
        
## 技术支持
        
不提供任何的技术支持，如果自动构建不正常或者有什么建议，请提出一个[新的Issue](https://github.com/yige-yigeren/MagiskOnWSAAuto/issues/new)。
        
关于Android™️子系统运行异常的问题请在MagiskOnWSA提出一个[新的Issue](https://github.com/LSPosed/MagiskOnWSALocal/issues/new/choose)。

## 关于版权

MagiskOnWSALocal is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

## 星标

如果这个项目有帮到你，请点个Star，这是对我努力的肯定ヾ(≧▽≦*)o。

<p align="center">
  <a href="https://star-history.com/#yige-yigeren//MagiskOnWSAAuto&Date">
    <img src="https://api.star-history.com/svg?repos=yige-yigeren/MagiskOnWSAAuto&type=Date" alt="Star History Chart">
  </a>
</p>

Copyright (C) 2023 Yige-Yigeren
