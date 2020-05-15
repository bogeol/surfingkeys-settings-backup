## 前言

官方介绍：Rich shortcuts to click links/switch tabs/scroll pages or capture full page, use your browser like vim for productivity.A Chrome extension for Vim users, but EMACS users would also love it, as it is much extendable with javascript.

简而言之：就是用键盘快捷键更方便的操作浏览器

## 一、简单配置

- 安装 -> 左键Surfingkeys插件 -> Settings -> Key mappings -> Advanced mode
- Loading settings from -> [SETTINGS](https://raw.githubusercontent.com/bogeol/surfingkeys-settings-backup/master/settings/bogeol-surfingkeys-settings.txt)
- 把上面链接复制进去 -> Save

## 二、常用按键

### 1.Move Page

| 按键 |      功能       |     备注      |
| :--: | :-------------: | :-----------: |
|  h   |      left       |       ←       |
|  j   |      down       |       ↓       |
|  k   |       up        |       ↑       |
|  l   |      right      |       →       |
|  u   |  scroll **u**p  | &lt;PG UP&gt; |
|  d   | scroll **d**own | &lt;PG DN&gt; |
|  gg  |  scroll to top  | &lt;HOME&gt;  |
|  G   |  scroll to end  |  &lt;END&gt;  |
|  r   |   **r**efresh   |   <Ctrl-R>    |

### 2.Move Tab

| 按键 |    功能    |       备注       |
| :--: | :--------: | :--------------: |
|  H   |  left tab  | <Ctrl-Shift-Tab> |
|  L   | right tab  |    <Ctrl-Tab>    |
|  x   | close tab  |     <Ctrl-W>     |
|  X   | reopen tab |  <Ctrl-Shift-T>  |

### 3.Move History

| 按键 |       功能       |    备注     |
| :--: | :--------------: | :---------: |
|  J   | forward history  | ↓往下是新的 |
|  K   | backward history | ↑往上是旧的 |

### 4.Search

| 按键  |               功能                |                       备注                        |
| :---: | :-------------------------------: | :-----------------------------------------------: |
| so/oo | search go**o**gle/open go**o**gle | s是搜索已复制或者选中的文字/o是打开搜索栏自行输入 |
| sb/ob |             **b**aidu             |                       同上                        |
| sd/od |          **d**uckduckgo           |                       同上                        |
| sg/og |            **g**ithub             |                       同上                        |
| ss/os |         **s**tackoverflow         |                       同上                        |
| st/ot |       google **t**ranslate        |              同上（可修改搜索参数）               |
| sy/oy |            **y**outube            |                       同上                        |

### 5.Mouse

| 按键 |                 功能                  |        备注        |
| :--: | :-----------------------------------: | :----------------: |
|  f   | 根据hint选择鼠标点击 (空格键隐藏hint) |    select click    |
|  i   |          根据hint选择输入框           |    select input    |
|  gi  |           选择第一个输入框            | select first input |

## 三、其他按键

### 1.标签页

- `g0` 跳转到第一个标签页
- `g$` 跳转到最后一个标签页
- `gx0` 关闭当前标签左侧所有标签
- `gx$` 关闭当前标签右侧所有标签
- `gxx` 关闭当前标签之外所有标签
- `<<` 左移当前标签
- `>>` 右移当前标签
- `gt` 选择所有已打开的标签页

### 2.打开浏览器内置功能

- `ga` About

- `gb` Bookmark

- `gc` Cache

- `gd` Download

- `gh` History

- `gk` Cookie

- `ge` Extension

- `gn` Net-Internal

- `gs` Source

### 3.会话

- `ZZ` 保存会话并退出
- `ZR` 恢复最近一次会话

### 4.剪切板

- `yy` 复制当前网页链接
- `yi` 复制输入框中的内容

### 5.BAR

- `t` 打开新网页bar
- `b` 打开收藏夹bar
- `ab` 添加到收藏夹
- `<Shift-Tab>` 在Bar中切到上一个条目
- `<Tab>` 在Bar中切到下一个条目
- `<Ctrl-,>` 在Bar中显示上一页搜索结果
- `<Ctrl-.>` 在Bar中显示下一页搜索结果

### 6.其他功能按键

- `?` 打开帮助
- `etc.`

## 四、总结

- 可以键盘鼠标配合操作浏览器（或者直接键盘操作 @狗头@）
- 可以自定义配置（自定义快捷键，自定义快捷键的功能）

