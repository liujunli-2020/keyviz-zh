# [Keyviz-zh](https://github.com/liujunli-2020/keyviz-zh)

> 🔰 本项目 Fork 自 [mulaRahul/keyviz](https://github.com/mulaRahul/keyviz)，汉化版。

<div>
   <img src="https://img.shields.io/github/v/release/liujunli-2020/keyviz-zh?style=flat-square" alt="Releases">
   <img src="https://img.shields.io/github/downloads/liujunli-2020/keyviz-zh/total?style=flat-square" alt="Downloads">
   <img src="https://img.shields.io/github/stars/liujunli-2020/keyviz-zh?style=flat-square" alt="Stars">
   <img src="https://img.shields.io/github/license/liujunli-2020/keyviz-zh?style=flat-square" alt="License">
   <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey?style=flat-square" alt="Platform Support">
</div>

Keyviz-zh 是一款**免费且开源**的工具，可以实时可视化你的按键和鼠标操作。让你在进行教程、演示、协作或其他场景时，观众能清楚地看到你按下了哪些快捷键。

**本仓库基于 [mulaRahul/keyviz](https://github.com/mulaRahul/keyviz) 进行汉化，主要改动为界面中文化，方便中文用户使用。**

## ⌨️ 按键 & 🖱️ 鼠标操作

除了普通按键外，还可以可视化鼠标操作，例如 <kbd>Cmd</kbd> + <kbd>单击</kbd>、<kbd>Alt</kbd> + <kbd>拖拽</kbd> 等。

<img src="previews/visualization.png" alt="按键可视化" width="450">

在光标旁边显示鼠标点击和滚轮移动。

<img src="previews/mouse-indicator.gif" alt="鼠标指示器" width="450">

</br>

## ⚙️ 完全自定义

不满足于默认设置。可视化的每个方面都可以由你掌控：
- **样式：** 更改颜色（修饰键 vs 普通键）、大小、布局、边框和背景。
- **过滤：** 使用快捷键或自定义过滤器控制显示哪些按键。
- **历史记录：** 保留最近输入的视觉轨迹。
- **位置：** 将可视化移动到屏幕的任意位置。
- **动画：** 使用预设的入场和退场动画自定义输入的出现和消失方式。

</br>

<img src="previews/settings.png" alt="设置面板" width="600">

</br>

## 📥 安装

### Windows & macOS
可以从 **[GitHub Releases](https://github.com/liujunli-2020/keyviz-zh/releases)** 页面下载最新版本。

*   **Windows：** 下载 `.msi` 安装程序，运行并按照步骤操作。
*   **macOS：** 下载 `.dmg`。
    **注意：** Keyviz-zh 需要**输入监控**和**辅助功能**权限。请在此处启用：
    `设置 > 隐私与安全性 > 输入监控与辅助功能`

### Linux (x11)
Keyviz-zh 兼容使用 X11 协议的 Linux 系统。目前你可以按照下面的构建说明来尝试。

</br>

## 🛠️ 构建说明

如果你想贡献代码或从源码构建最新功能，请确保系统上已安装 [Node.js](https://nodejs.org/) 和 [Tauri](https://v2.tauri.app/start)。

1.  **克隆仓库：**
    ```bash
    git clone https://github.com/liujunli-2020/keyviz-zh.git
    cd keyviz-zh
    ```

2.  **安装依赖：**
    ```bash
    npm install
    ```

3.  **构建可执行文件：**
    ```bash
    npx tauri build
    ```

<br/>


## 💖 支持项目

*   **Star 仓库：** 帮助更多人发现这个项目！
*   **赞助原作者：** [Sponsor @mulaRahul](https://github.com/sponsors/mulaRahul)
*   **Keyviz Pro：** 获取独家功能，同时支持这个开源项目的开发。

👉 **[升级到 Pro 版 at keyviz.org/pro](https://keyviz.org/pro)**

</br>

---

## 📝 关于汉化版

- **Fork 自：** [mulaRahul/keyviz](https://github.com/mulaRahul/keyviz)
- **改动内容：** 界面中文化（简体中文）
- **上游版本：** 跟随上游最新版本同步更新

Built with 🦀 and ❤️ using <a href="https://v2.tauri.app/">Tauri</a>.
