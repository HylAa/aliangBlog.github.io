---
title: Github Copilot 的使用方法和快捷键
tags:
  - Vscode
categories: []
date: 2021-01-15 17:15:00
updated: 2021-01-15 17:15:00
top_img: https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649145740/WX20220405-160150_hkvi4q.png
cover: https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649145740/WX20220405-160150_hkvi4q.png
sticky: 1
---


## Copilot 是什么

Copilot (<https://copilot.github.com/>) 是由 Github 提供的AI编码辅助工具，它可以在编码过程中提供基于 AI 学习的编码建议。在很多情况下，只需要有注释或者函数名称，Copilot就可以实例完整的代码。

目前 Copilot 还没有全量开放，需要申请开通权限。访问它的官方网站<https://copilot.github.com/>，点击“Sign up“按钮即可申请开通。当获得开通权限后，就可以在 Github 上使用 Copilot。


![官网截图](https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649145740/WX20220405-160150_hkvi4q.png)

## 安装插件

使用 Copilot 时，需要安装一个插件，在 VSCode 的插件菜单中搜索 `Copilot`，即可找到插件，名字为 `Github Copilot`，对应的插件市场的地址为<https://marketplace.visualstudio.com/items?itemName=GitHub.copilot>，安装即可。

![安装截图](https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649146016/2051649145951_.pic_q03uk2.png)

安装后插件会提示要求登录 Github ，按提示登录即可。

![登录截图](https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649146070/03.login_qn7mvg.png)

## 使用

正常使用时，当 Copilot 给出建议时，会在光标位置的后方出现建议的代码，并灰色字显示。如果不希望使用提示，则继续输入代码即可，如果希望使用提示的代码，按下 Tab 键即可。

![使用截图](https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649146200/04.completion_ctsnl0.png)

在 VSCode 中，Copilot 有一个图标，需要确认状态是打开的。当它的样子与其它图标类似，没有背景颜色时，表示是开启的，此时当你编辑代码文件的时候，Copilot会自动提示代码建议。当它有背景颜色（红色、深黄色等）时，表示是关闭的。如果要切换状态只要点击它，然后选择全局（Globally）即可。

![状态图标](https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649146129/05.icon_zyh6um.png)

## 快捷键

Copilot 也提供了一些快捷键，可以很方便地使用。

- 接受建议：`Tab`
- 拒绝建议：`Esc`
- 打开Copilot：`Ctrl + Enter` （会打开一个单独的面板，展示10个建议）
- 下一条建议：`Alt/Option + ]`
- 上一条建议：`Alt/Option + [`
- 触发行内Copilot：`Alt/Option + \` （Coplit还没有给出建议或者建议被拒绝了，希望手工触发它提供建议）
  

![状态图标](https://res.cloudinary.com/dt3vcmqdt/image/upload/v1649146130/06.shortcut_afyn4j.jpg)


## JetBrains IDE
#### macOS 的键盘快捷键

| 行动 | 捷径 |
|------|------|
| 接受内联建议 | Tab |
| 拒绝内联建议 | Esc |
| 显示下一个内联建议 | Option (⌥) or Alt+] |
| 显示上一个内联建议 | Option (⌥) or Alt+[ |
| 触发内联建议 | Option (⌥)+\ |
| 打开 GitHub Copilot（其他建议在单独的窗格中） | Option (⌥) or Alt+Return |

#### 适用于 Windows 的键盘快捷键

| 行动 | 捷径 |
|------|------|
| 接受内联建议 | Tab |
| 拒绝内联建议 | Esc |
| 显示下一个内联建议 | Alt+] |
| 显示上一个内联建议 | Alt+[ |
| 触发内联建议 | Alt+\ |
| 打开 GitHub Copilot（其他建议在单独的窗格中） | Alt+Enter |

#### Linux 的键盘快捷键

| 行动 | 捷径 |
|------|------|
| 接受内联建议 | Tab |
| 拒绝内联建议 | Esc |
| 显示下一个内联建议 | Alt+] |
| 显示上一个内联建议 | Alt+[ |
| 触发内联建议 | Alt+\ |
| 打开 GitHub Copilot（其他建议在单独的窗格中） | Alt+Enter |



## Visual Studio Code IDE

### macOS 的键盘快捷键

| 行动 | 捷径 | 命令名称 |
|------|-----|----------|
| 接受内联建议 | Tab | 编辑器.action.inlineSuggest.commit |
| 拒绝内联建议 | Esc | editor.action.inlineSuggest.hide |
| 显示下一个内联建议 | Option (⌥)+] | editor.action.inlineSuggest.showNext |
| 显示上一个内联建议 | Option (⌥)+[ | editor.action.inlineSuggest.showPrevious |
| 触发内联建议 | Option (⌥)+\ | 编辑器.action.inlineSuggest.trigger |
| 打开 GitHub Copilot（其他建议在单独的窗格中） | Ctrl+Return | github.copilot.generate |
| 打开/关闭 GitHub Copilot | 没有默认快捷方式 | github.copilot.toggleCopilot |

### 适用于 Windows 的键盘快捷键

| 行动 | 捷径 | 命令名称 |
|------|-----|----------|
| 接受内联建议 | Tab | 编辑器.action.inlineSuggest.commit |
| 拒绝内联建议 | Esc | editor.action.inlineSuggest.hide |
| 显示下一个内联建议 | Alt+] | editor.action.inlineSuggest.showNext |
| 显示上一个内联建议 | Alt+[ | editor.action.inlineSuggest.showPrevious |
| 触发内联建议 | Alt+\ | 编辑器.action.inlineSuggest.trigger |
| 打开 GitHub Copilot（其他建议在单独的窗格中） | Ctrl+Enter | github.copilot.generate |
| 打开/关闭 GitHub Copilot | 没有默认快捷方式 | github.copilot.toggleCopilot |

### Linux 的键盘快捷键

| 行动 | 捷径 | 命令名称 |
|------|-----|----------|
| 接受内联建议 | Tab | 编辑器.action.inlineSuggest.commit |
| 拒绝内联建议 | Esc | editor.action.inlineSuggest.hide |
| 显示下一个内联建议 | Alt+] | editor.action.inlineSuggest.showNext |
| 显示上一个内联建议 | Alt+[ | editor.action.inlineSuggest.showPrevious |
| 触发内联建议 | Alt+\ | 编辑器.action.inlineSuggest.trigger |
| 打开 GitHub Copilot（其他建议在单独的窗格中） | Ctrl+Enter | github.copilot.generate |
| 打开/关闭 GitHub Copilot | 没有默认快捷方式 | github.copilot.toggleCopilot |
