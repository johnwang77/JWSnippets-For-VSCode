# JWSnippets For VSCode
---
### 引言
专为**VSCode**开发微信小程序编写的Snippet。
### (很快更新js和json文件的sinppet，联系作者，欢迎提供代码段)

### 版本更新
---
| 时间 | 版本号 | 更新内容 |
|--------|------------|---------------|
| 2016.09.25 | 1.0 | 上传html.json |

### 安装使用
---
**1.将json文件放入vscode的sinppets目录：**
- Windows版本：C:\Users\用户名\AppData\Roaming\Code\User\snippets
- Mac版本：/Users/用户名/Library/Application Support/Code/User/snippets

**2.VSCode菜单->首选项->用户设置，在settings.json加入以下代码：**

```
"files.associations": { "*.wxml": "html", "*.wxss": "css"}
```

**3.为防止和其他命令冲突，本sinppet触发命令以'jw'开头。**

### 组件命令列表：
---

组件命令 | 命令说明 | 组件命令 | 命令说明
---|---|---|---
jwview | 创建view组件 | jwradio-group | 创建radio-group组件
jwscroll-view | 创建组件 | jwradio | 创建radio组件
jwswiper | 创建swiper组件 | jwslider | 创建slider组件
jwicon | 创建icon组件 | jwswitch | 创建switch组件
jwtext | 创建text组件 | jwaction-sheet | 创建action-sheet组件
jwprogress | 创建progress组件 | jwmodal | 创建modal组件
jwbutton | 创建button组件 | jwtoast | 创建toast组件
jwcheckbox-group | 创建checkbox-group组件 | jwloading | 创建loading组件
jwcheckbox| 创建checkbox组件 | jwnavigator | 创建navigator组件
jwform | 创建form组件 | jwaudio | 创建audio组件
jwinput | 创建input组件 | jwimage | 创建image组件
jwlabel | 创建label组件 | jwvideo | 创建video组件
jwpicker-selector | 创建picker-selector组件 | jwmap | 创建map组件
jwpicker-time | 创建picker-time组件 | jwcanvas | 创建canvas组件
jwpicker-date | 创建picker-date组件

### 作者相关：
---
- 简书：http://www.jianshu.com/users/bbeb5d67076e
- GitHub：https://github.com/johnwang77/JWSnippets-For-VSCode
