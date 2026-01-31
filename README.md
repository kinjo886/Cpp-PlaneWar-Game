✈️ C++ 飞机大战 (Plane War)

一个基于 C++ 和 EasyX 图形库开发的经典竖版射击游戏。
从底层逻辑实现到美术素材绘制，全流程独立开发。

📖 项目简介

这是一个经典的飞机大战游戏复刻项目。作为我的 C++ 编程实践作品，本项目没有使用现成的游戏引擎，而是基于 EasyX 图形库 从零构建了游戏循环、渲染逻辑和物理碰撞系统。

通过该项目，我深入理解了 面向对象编程 (OOP) 的思想，封装了战机、敌机、子弹等游戏实体，并处理了简单的内存管理。

🎮 游戏演示 (Demo)

<!-- 💡 提示：请运行你的游戏，截图并保存。在 GitHub 编辑框里，直接把图片拖到这里，它会自动生成链接 -->

(游戏运行画面：展示了玩家射击、敌机生成及得分界面)

✨ 核心功能

流畅的操控体验：支持键盘/鼠标控制战机移动与射击。

敌机生成算法：实现了敌机的随机生成与移动逻辑，难度随时间线性增加。

碰撞检测系统：基于矩形包围盒 (AABB) 实现了精准的子弹打击与坠机判定。

原创美术素材：游戏内的核心素材（战机、UI）均为个人使用手绘板绘制。

音效反馈：集成了背景音乐与击打音效，提升沉浸感。

🛠️ 技术栈

开发语言: C++ (STL)

开发环境: Visual Studio 2022

图形库: EasyX Graphics Library

美术工具: SAIVer2 (手绘素材)

📂 项目结构

PlaneWar/
├── 📂 res/               # 游戏资源文件夹 (图片、音效)
├── 📄 Source.cpp         # 游戏主入口 (Main Loop)
├── 📄 AirPlay.h          # 战机/游戏实体类定义
├── 📄 tools.cpp          # 辅助工具函数
├── 📄 list.h             # 链表结构 (用于管理子弹/敌机队列)
└── 📄 PlaneWar.sln       # Visual Studio 解决方案文件


🚀 如何运行 (How to Run)

环境准备：

确保已安装 Visual Studio (推荐 2019 或 2022)。

下载并安装 EasyX 图形库 (一键安装到 VS)。

获取代码：

git clone [https://github.com/kinjo886/Cpp-PlaneWar-Game.git](https://github.com/kinjo886/Cpp-PlaneWar-Game.git)


编译运行：

双击打开目录下的 PlaneWar.sln 文件。

在 Visual Studio 顶部工具栏选择 Debug 或 Release 模式 (x86/x64 需根据 EasyX 版本匹配)。

点击 本地 Windows 调试器 (Local Windows Debugger) 即可启动游戏。

👨‍💻 作者信息

吴俊 (Wu Jun)

Role: C++ Developer / Game Planner

Email: 23jwu2@stu.edu.cn

More Projects: 访问我的简历主页

感谢您的观看！如果觉得项目不错，欢迎点一个 Star ⭐️
