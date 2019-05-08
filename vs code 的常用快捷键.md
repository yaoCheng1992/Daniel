> **vs code 的常用快捷键**

------

> **1、注释：**
>
> 　　**a) 单行注释：[ctrl+k,ctrl+c] 或 ctrl+/**
>
> 　　**b) 取消单行注释：[ctrl+k,ctrl+u] (按下ctrl不放，再按k + u)**
>
> 　　**c) 多行注释：[alt+shift+A]**
>
> 　　**d) 多行注释：**/**

------

> **2、****移动行：alt+up/down**
>
> **3、显示/隐藏左侧目录栏 ctrl + b**
>
> **4、复制当前行：shift + alt +up/down**
>
> **5、删除当前行：shift + ctrl + k**
>
> **6、控制台终端显示与隐藏：ctrl + ~**
>
> **7、查找文件/安装vs code 插件地址：ctrl + p**

------

> **8、代码格式化：shift + alt +f**
>
> **9、新建一个窗口 : ctrl + shift + n**
>
> **10、行增加缩进: ctrl + [**
>
> **11、行减少缩进: ctrl + ]**
>
> **12、裁剪尾随空格(去掉一行的末尾那些没用的空格) : ctrl + shift + x**
>
> **13、字体放大/缩小: ctrl + ( + 或 - )**
>
> **14、拆分编辑器 : ctrl + 1/2/3**
>
> **15、切换窗口 : ctrl + shift + left/right**

------

> **16、****关闭编辑器窗口 : ctrl + w**
>
> **17、关闭所有窗口 : ctrl + k + w**
>
> **18、****切换全屏 : F11**
>
> **19、****自动换行 : alt + z**
>
> **20、****显示git : ctrl + shift + g**
>
> **21、****全局查找文件：ctrl + shift + f**
>
> **22、****显示相关插件的命令(如：git log)：ctrl + shift + p**
>
> **23、****选中文字：shift + left / right / up / down**
>
> **24、****折叠代码： ctrl + k + 0-9 (0是完全折叠)**
>
> **25**、***展开代码： ctrl + k + j (完全展开代码)**
>
> **27、快速切换主题：ctrl + k / ctrl + t**
>
> **28、快速回到顶部 ： ctrl + home**
>
> **29、快速回到底部 : ctrl + end**
>
> **30、格式化选定代码 ：ctrl + k / ctrl +f**

#### 1、关于 窗口 的操作

- 新开窗口：ctl + shift + n
- 关闭窗口：ctrl + shift + w
- 放大/缩小字号：ctrl + +/-
- 显示和隐藏侧边栏：Ctrl + B

#### 2、关于 分栏 的操作

- 新建一个分栏（编辑器）：ctrl + \ （最多允许三个分栏）
- 选中某个分栏：ctrl + 1/2/3 数字表示要选中的是第几个分栏

#### 3、关于 文件 的操作

- 新建文件: ctrl + n
- 关闭当前文件：ctrl + F4
- 打开文件： ctrl + o
- 打开的文件之间切换：ctrl + tab

#### 4、关于 行 的操作

- 新开一行：光标在行尾的话，回车即可；光标不在行尾，ctrl + enter 向下重开一行；ctrl + shift + enter 则是在上一行重开一行
- 删除一行：光标没有选择内容时，ctrl + x 剪切一行；ctrl + shift + k 直接删除一行
- 移动一行：alt + ↑ 向上移动一行；alt + ↓ 向下移动一行
- 复制出一行：alt + shift + ↓ 向下复制一行；alt + shift + ↑ 向上复制一行
- 复制或剪切当前行/当前选中内容到剪切板：Ctrl+C
- 粘贴：ctrl + v
- 代码行缩进：减少缩进 Ctrl + [ 、 增加缩进 Ctrl + ]

#### 5、关于 词 的操作

- 选中一个词：ctrl + d
- 搜索/替换：

ctrl + f ：搜索 ctrl + alt + f： 替换 ctrl + shift + f：在项目内搜索

格式化整个文件的代码：shift + alt + f

#### 6、关于 光标 的操作

- 移动到行首： Home
- 移动到行尾： End
- 移动到文件开头： Ctrl + Home
- 移动到文件结尾： Ctrl + End
- 选择从行首到光标处： Shift + Home
- 选择从光标到行尾： Shift + End
- 删除光标右侧的所有字： Ctrl + Delete
- 多行编辑（列编辑）：Alt + Shift + 鼠标左键
- 同时选中所有匹配： Ctrl + Shift + L
- 下一个匹配的也被选中：Ctrl + D
- 回退上一个光标操作： Ctrl + U

#### 7、关于 主命令框 的操作

打开命令面板：ctrl + shift + p

在打开的输入框内，可以输入任何命令。按一下 Backspace 会进入到 Ctrl + P 模式。

在 Ctrl + P 模式下输入 `>` 可以进入 Ctrl + Shift + P 模式

在 Ctrl + P 窗口下还可以:

直接输入文件名，跳转到文件：

`?` 列出当前可执行的动作

`!` 显示 Errors或 Warnings，也可以 Ctrl + Shift + M

`:` 跳转到行数，也可以 Ctrl+G 直接进入

`@` 跳转到 symbol（搜索变量或者函数），也可以 Ctrl + Shift + O 直接进入

`@` 根据分类跳转 symbol，查找属性或函数，也可以 Ctrl + Shift + O 后输入`:`进入

`#` 根据名字查找 symbol，也可以 Ctrl + T