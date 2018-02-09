# pycharm使用教程

- 新建项目：Pure Python
> Location
> Interpreter  
> 新建文件：Python file  
> 预加载：耗费初始化时间；> 每次关闭时点击File>>Close Project，可消除这一弊端，但是可能会不方便  

- 配置解释器：File>>Settings/Default(Import/Export)Settings/Setting Repository
> Project:项目名称  
> Project Interpreter:修改解释器，apply  

- 安装模块
> Project Interpreter:“+”号；搜索，Install Package

- python文本编辑
> 设计字体：Settings>>Appearance& Behavior，风格，大小；Settings>>Editor>>Colors & Fonts>>Font

- 设置编码  
> Settings>>Editor>>File Encodings:最好将全局、项目、默认编码都设置为“UTF-8”，重启编辑器生效

- 设置脚本头
> Settings>>Editor>>Code Style>>File and Code Templates>>
>  #! /usr/bin/env python  
>  # -*- coding:utf-8 -*-  
>  # author: ${USER} time:${DATE}  
>  为了兼容Python2和Python3，最好都加入脚本头

- 写代码时，代码下方的波浪线
> 软件自带的文本检测功能：代码规范
> 选中文本>>右键>>Spelling>>Type: Save '文本' to dictionary

- 复制路径
> py文件>>右键>>Copy Path

- 打开文件所在目录
> py文件>>右键>>Show in Explorer
  
- Structure：文档结构  
> 右侧，与Project平行  
> v：变量；f：函数；c：类  
 
-  \# TODO：记录要做的事情  
> 当项目工程较大时

- debug：调试
> 编辑代码窗口，右键>>debug 'aaa(文件名)'
> 下面出来的窗口中有调试菜单
> 在程序关键的地方使用


- 快捷键设置  
> Setting>>Keymap>>Editor Actions  

- 快捷键  
> Ctrl+D：复制一行代码  
> Ctrl+Y：删除一行代码  
> Shift+Enter：快速换行（从较长的代码行转到下一行代码）  
> Ctrl+鼠标左键：快速定位，查询信息  
> Ctrl+“/”（先选中文本行）：批量注释/批量取消注释  
> Tab（先选中文本行）：批量快速缩进  
> Shift+Tab：批量取消缩进  
> Ctrl+F：查找  
> Ctrl+R（replace）：替换；可以用正则表达式  
> Ctrl+“-”：当前代码折叠  
> Ctrl+“+”：当前代码展开
> Ctrl+Shift+“-”：所有代码折叠  
> Ctrl+Shift+“+”：所有代码展开  





