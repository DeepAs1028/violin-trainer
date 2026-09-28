<div align="right">
  <strong><a href="#chinese-version">🇨🇳 简体中文</a></strong> | <strong><a href="#english-version">🇬🇧 English</a></strong>
</div>

---

<h1 id="chinese-version">Violin Master: 小提琴音感与指法交互训练器</h1>

> **Design for Engineer Thinking** —— 专为逻辑思维型学习者打造的小提琴初学者辅助工具。

学小提琴初期，大脑需要同时处理“看谱 -> 认音 -> 找弦 -> 按指”这一系列复杂的翻译流程，初学者往往会感到手忙脚乱。本项目旨在通过**“交互式视觉与肌肉记忆绑定”**，跳过传统的死记硬背，帮助初学者快速建立五线谱、音名与小提琴第一把位指法的直觉反射。

👉 **[在线运行体验：小提琴音感与指法交互训练器](https://DeepAs1028.github.io/violin-trainer/)**

## 💡 为什么做这个项目？

传统的练琴方式容易让学习者卡在“读谱翻译”这一步。本项目采用“工程师思维”，将复杂的认谱过程拆解为可量化、可即时反馈的模块。通过像打游戏一样的随机抽题和即时正误判定，强迫大脑建立**“视觉坐标 -> 物理动作”**的直接映射，极大缩短新手期的痛苦挣扎。

## ✨ 核心功能模块

本程序包含四个循序渐进的训练模式，全面覆盖初学者的识谱痛点：

*   **模式 1：视觉反射（看谱 -> 输指法）**
    *   **场景**：屏幕随机显示五线谱音符（包含上下加线）。
    *   **任务**：不需要唱出音名，直接在键盘输入对应的弦和指法（如 `A1`、`G3`）。
    *   **目的**：建立五线谱黑点位置与左手手指动作的直接绑定。
*   **模式 2：脑图映射（看名 -> 输指法）**
    *   **场景**：屏幕提示特定音高（如“Sol (中)”）。
    *   **任务**：输入该音高对应的提琴指法（如 `D3`）。
    *   **目的**：脱离五线谱，纯粹训练大脑对音阶在琴弦空间分布的熟悉度。
*   **模式 3：交互定位（看名 -> 点选五线谱）**
    *   **场景**：屏幕提示音高，你需要用鼠标在空白五线谱上点击正确的位置。
    *   **特色**：支持鼠标悬停“幽灵音符”预览及自动加线，点击后即时反馈颜色（绿对红错）。
    *   **目的**：反向训练，提升对五线谱线间逻辑的结构化认知。
*   **模式 4：绝对认音（看谱 -> 选音名）**
    *   **场景**：五线谱出现音符，下方提供 C D E F G A B 七个按钮。
    *   **任务**：点击对应的绝对音名。
    *   **目的**：回归基础乐理，强化绝对音高的快速识别能力。

## 🚀 极简部署与使用

本项目采用极其轻量级的原生前端技术栈（HTML5 Canvas + JavaScript）开发。

1.  **零依赖、零安装**：没有任何后台服务器或复杂的环境配置。
2.  **开箱即用**：只需下载项目中的 `index.html` 文件，双击使用任何现代浏览器（Chrome, Edge, Safari等）打开即可开始训练。
3.  **跨平台支持**：支持打包部署至 GitHub Pages，生成网页链接后，手机、平板、电脑均可随时随地访问练习。

## 🎯 适合人群

*   正在学习小提琴第一把位，对五线谱加线区（G弦低音、E弦高音）不敏感的初学者。
*   习惯用逻辑和坐标系来理解乐理的成年人/理工科背景学习者。
*   需要脱离提琴实体，在通勤或碎片时间进行“意念练琴”的音乐爱好者。

---
*如果你在使用过程中发现任何逻辑错误（例如音位对应有误），或者有更好玩的训练模式建议，欢迎提交 Issue，或直接反馈至开发者邮箱：[deepas@foxmail.com](mailto:deepas@foxmail.com)。祝你练琴愉快！*

<br><br>

---

<h1 id="english-version">Violin Master: Interactive Pitch & Fingering Trainer</h1>

> **Design for Engineer Thinking** — An auxiliary tool tailored for logical thinkers beginning their violin journey.

In the early stages of learning the violin, the brain must simultaneously process a complex translation workflow: "read sheet music -> recognize note -> locate string -> place finger," which often overwhelms beginners. This project aims to bypass traditional rote memorization through **"interactive visual and muscle memory binding."** It helps beginners quickly establish intuitive reflexes between sheet music, note names, and violin first-position fingerings.

👉 **[Live Demo: Violin Pitch & Fingering Interactive Trainer](https://DeepAs1028.github.io/violin-trainer/)**

## 💡 Why Build This Project?

Traditional practice methods often leave learners stuck at the "sheet music translation" step. Adopting an "engineer's mindset," this project breaks down the complex sight-reading process into quantifiable modules with instant feedback. Like playing a game, randomized quizzes and immediate correctness checks force the brain to build a direct mapping between **"visual coordinates -> physical actions,"** significantly reducing the struggle of the beginner phase.

## ✨ Core Features

This application features four progressive training modes, comprehensively covering beginners' sight-reading pain points:

*   **Mode 1: Visual Reflex (Sheet Music -> Fingering)**
    *   **Scenario**: The screen randomly displays sheet music notes (including ledger lines).
    *   **Task**: No need to sing the note name; input the corresponding string and fingering directly on your keyboard (e.g., `A1`, `G3`).
    *   **Purpose**: Establish a direct binding between the position of the note on the staff and the physical action of the left fingers.
*   **Mode 2: Mental Mapping (Note Name -> Fingering)**
    *   **Scenario**: The screen prompts a specific pitch (e.g., "Sol (Mid)").
    *   **Task**: Input the corresponding violin fingering for that pitch (e.g., `D3`).
    *   **Purpose**: Detach from sheet music to purely train the brain's familiarity with the spatial distribution of scales across the strings.
*   **Mode 3: Interactive Positioning (Note Name -> Click Staff)**
    *   **Scenario**: The screen prompts a pitch, and you need to click the correct position on a blank staff using your mouse.
    *   **Features**: Supports "ghost note" hover previews and automatic ledger lines, with instant color feedback upon clicking (green for correct, red for incorrect).
    *   **Purpose**: Reverse training to enhance structured understanding of the staff's line and space logic.
*   **Mode 4: Absolute Pitch Recognition (Sheet Music -> Select Note Name)**
    *   **Scenario**: A note appears on the staff, with C D E F G A B buttons provided below.
    *   **Task**: Click the corresponding absolute note name.
    *   **Purpose**: Return to basic music theory to strengthen rapid recognition of absolute pitches.

## 🚀 Minimalist Deployment & Usage

This project is developed using an extremely lightweight native frontend tech stack (HTML5 Canvas + JavaScript).

1.  **Zero Dependencies, Zero Installation**: No backend servers or complex environment configurations required.
2.  **Out-of-the-Box**: Simply download the `index.html` file and open it with any modern browser (Chrome, Edge, Safari, etc.) to start training.
3.  **Cross-Platform Support**: Supports packaging and deployment to GitHub Pages. Once a web link is generated, it can be accessed on phones, tablets, or computers anytime, anywhere.

## 🎯 Target Audience

*   Beginners learning the violin's first position who struggle with ledger lines (low notes on the G string, high notes on the E string).
*   Adults or learners with a STEM background who prefer understanding music theory through logic and coordinate systems.
*   Music lovers who want to practice "mentally" during commutes or fragmented time without needing the physical instrument.

---
*If you find any logical errors during use (e.g., incorrect note mappings), or have suggestions for fun new training modes, feel free to submit an Issue or contact the developer directly at: [deepas@foxmail.com](mailto:deepas@foxmail.com). Happy practicing!*
