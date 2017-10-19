## `ACMer`桌面集成工具

### 项目介绍

#### 目的

> 竞赛圈愈来愈庞大，各种黑科技每年层出不穷，但是缺乏一种简单便捷的方法，本工具意在方便各位竞赛生愉悦码题、开心AC

#### 功能

- 代码高亮功能

  **基本：** 支持基本的**代码浏览编辑**和**颜色高亮**（格式：`Monaco`）

  **提高：** 支持`gcc`编译运行，变成轻量级IDE

- 随机化生成数据功能

  **基本：** 支持根据用户需求和设置，随机化生成各种规模的数据，便于不同题型的测试，随机功能包括但不限于以下几类——

  - 带**上下限**和**组数**的随机整数、小数、分数、字符
  - 按**深度、节点数、边数**随机生成一棵或多课**树**，包括但不限于——
    - 带**点权**树
    - 带**边权**树
    - 完全**k叉**树
    - 满**k叉**树

- 程序对拍功能

  **基本：** 根据用户提供的**标准程序**和**用户程序**和**随机化程序**自动对拍，并返回结果

  **提高：** 省去_随机化程序_ 费时费力，根据用户设置参数结合_功能二_ 自动化随机程序

- 代码管理功能

  **基本：** 根据用户需求按**算法**或**项目**分类，使得用户代码工程逻辑可视化，按逻辑浏览-访问

- 阅读、编辑功能

  **基本：** 实现可视化编辑`markdown`格式（左侧源文，右侧即时效果，相当于小型markdown编辑器）；支持`PDF`格式浏览。

  **提高：** 支持主流博客编辑一键发布和浏览功能。
