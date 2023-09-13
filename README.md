# codemap

[codemap](https://codemap.info)是一款集合代码结构可视化、高亮、标注等多种辅助阅读手段，现目前已经支持javascript、typescript、c、c++、python、golang、java等多种编程语言的辅助阅读源代码工具。通过codemap，即使是初学者也能顺利快速地阅读复杂开源项目，通过代码编辑器平铺布局、跳转结构自动连线、手动添加高亮、标注等形式，使代码结构清晰易懂，对于分析复杂项目的框架结构具有极其重大的作用，能成倍地提高用户阅读源代码的效率。

⚠️ **注意：codemap是非开源项目，本仓库仅用来管理需求和用户反馈。**

官方网站：https://codemap.info

使用示例：

![分析AnimatedDrawings](/assets/演示视频.gif)

## codemap已实现核心功能

- [x] 代码编辑器列式平铺布局，并支持拖拽、滑动等操作
- [x] 支持绝大多数编程语言的渲染
- [x] 支持自动跳转，并产生连线，连线起止位置随着代码编辑器移动、滑动或滚动自动更新
- [x] 支持手动添加自定义连线
- [x] 支持添加高亮、标注，并删除等辅助阅读源代码功能
- [x] 支持最佳折叠，始终保持编辑过的代码在最顶层显示
- [x] 支持最佳插入算法，当自动跳转需要新增代码编辑器时，codemap会通过算法自动计算出最佳的插入位置
- [x] 支持缩放、还原
- [x] 支持多tab页显示以及管理等功能
- [x] 支持编辑器和资源树联动，在资源树中快速显示已经编辑或者打开的文件，方便阅读
- [x] 通过lsp(language server protocol)协议，支持javascript、typescript、c 、c++、python、go、java等多种语言插件，支持他们的语法解析、自动跳转等功能
- [x] 支持windows、mac（intel芯片）、mac（apple芯片）等多操作系统
- [x] 用户系统

实战截图：

![AnimatedDrawings结构分析](/assets/AnimatedDrawings-debug后.jpg)

## 交流反馈

加我微信（备注加群），拉你进群。

<img src="/assets/二维码codemap-support.jpg" alt="微信二维码" width="240" height="240" />
