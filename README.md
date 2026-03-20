# Gusu-in-Paintings：VR-Enhanced Digital Scrolls: Immersive Experiences of Traditional Chinese Painting
An immersive VR system that reconstructs key historical scenes from Qiu Ying’s scroll. 
### VR 增强数字长卷：中国传统绘画沉浸式体验系统

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Unity](https://img.shields.io/badge/Platform-Unity-blue.svg)](https://unity.com/)

##Introduction
本项目旨在解决传统博物馆展示长卷绘画时存在的“认知负荷过重”和“参与度低”的问题。我们以 **仇英版《清明上河图》** 为蓝本，利用 VR 技术重建了其中的典型 3D 场景与人物，将静态的长卷转化为可交互的沉浸式世界。

通过本系统，用户可以以第一人称视角进入画作，与 NPC 互动，深入了解明代社会的文化知识与生活百态。

---

##  System Features

### 1. 双重交互模式 (Dual Exploration Modes)
根据研究需求，系统设计了两种不同的探索路径：
* **线性引导模式 (Mode 1: Linear Mode)**：
    * **叙事驱动**：跟随预设的剧情发展（如跟随“徐仲”官员视角）。
    * **剧情流程**：两位官员会面 ➔ 视察粮仓 ➔ 书画赏析 ➔ 居家待客。
    * **交互**：包含丰富的 NPC 对话交互，指引用户完成特定任务。
* **自由探索模式 (Mode 2: Open Mode)**：
    * **高自主性**：用户可从场景地图中任意选择感兴趣的区域进入。
    * **自主触发**：无特定剧情锁定，用户按需探索知识点。

### 2. 核心交互功能
* **NPC 对话系统**：支持与画中人物进行对话，获取历史背景信息。
* **多维知识展示**：通过放大镜（观察）、书籍（阅读）、电视（视频讲解）和喇叭（音频）图标触发交互。
* **沉浸式还原**：使用 Unity 和 Blender 1:1 还原明代建筑、服饰与生活场景。

---

## Tech Stack
* **开发引擎**: Unity
* **建模工具**: Blender (3D 场景与人物建模)
* **交互逻辑**: C# / Unity XR Interaction Toolkit
* **适配硬件**: VR 头显及控制器 (如 Meta Quest 2/3, HTC Vive)

---

##  Installation
> **注意：** 由于本项目包含大量高精度 3D 素材及纹理，压缩包体积约为 **3GB**。为保证仓库整洁，建议通过 Release 页面下载资源。

1.  **克隆基础仓库**：
    ```bash
    git clone [https://github.com/你的用户名/仓库名.git](https://github.com/你的用户名/仓库名.git)
    ```
2.  **获取大文件资源**：
    * 前往仓库右侧的 [Releases](https://github.com/你的用户名/仓库名/releases) 页面。
    * 下载所有分卷压缩包（如 `Game_Data.7z.001`, `Game_Data.7z.002`）。
    * 解压后将资源放入项目对应的 `Assets` 或直接运行打包好的 `.exe` 文件。

---

##  User Study
我们对 22 名参与者进行了对比实验，评估两种模式对传统文化学习的影响：
* **知识获取 (Knowledge Acquisition)**：两种模式均能显著提升用户对绘画知识的掌握，但线性引导模式在知识提升幅度上表现更优。
* **沉浸感与兴趣**：IMI（内在动机量表）和 FSS（沉浸感量表）测试显示，用户在两种模式下均维持了极高的参与度与兴趣。

---

## Team Members
* **指导老师 (Supervisors)**: Dr. Yu Liu
* **学生团队 (Students)**: Yuanyuan Peng, Suxuan Liu, Yutong Zhou, Jiawen Cai, Jiayu Wang, Yihan Fu,Yuhan Guo

---

##  System Preview
![System Flowchart](.system.png)
*图 1: 系统交互逻辑与模式选择流程图*

---
© 2025 SURF 项目组 - 致力于传统文化的数字化沉浸传播
