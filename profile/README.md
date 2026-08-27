# TensorGear

**宁波大学医工院 · 医学工程与人工智能研究组**

Medicine × AI · Ningbo University Institute of Medical Engineering

---

## 我们做什么

面向医工交叉的 AI 工具研发，当前聚焦**啮齿类动物行为学**的自动化分析：

- 🐭 **水迷宫（Morris water maze）** — 小鼠轨迹追踪、平台定位、U-Net 分割
- 🏊 **强迫游泳 / 悬尾实验** — 不动时间等行为学参数的自动判定
- 🌀 **Y 迷宫** — 自发交替行为的量化
- 🖥️ 完整工具链：视频采集 → 标注 → 训练 → 推理 → 导出

## 技术栈

PyTorch · OpenCV · U-Net · FastAPI · React/Vite · SAM

## Active Projects

### Animal Behavior

- **[animal-platform](https://github.com/TensorGear/animal-platform)** — Water Maze、Y-Maze 与 Forced Swim 的统一分析平台。

### Paper Experiments

- **[ultron](https://github.com/TensorGear/ultron)** — CalMS21 Mamba/keypoint 行为识别实验主线。
- **[train-harness](https://github.com/TensorGear/train-harness)** — 训练实验生命周期、基线和证据管理。
- **[hstwformer](https://github.com/TensorGear/hstwformer)** — HSTWFormer CalMS21 复现与扩展。
- **[hstwformer-baseline](https://github.com/TensorGear/hstwformer-baseline)** — 固定 pose-only 对照基线。
- **[msgl-repro](https://github.com/TensorGear/msgl-repro)** — MSGL Transformer CalMS21 复现。
- **[calms21-experiments](https://github.com/TensorGear/calms21-experiments)** — 论文实验报告与可复现证据。
- **[sam3-calms21-runner](https://github.com/TensorGear/sam3-calms21-runner)** — SAM3 CalMS21 mask runner。

### Industry Projects

- **[youzhi](https://github.com/TensorGear/youzhi)** — drill/line U-Net 训练与工业视频推理。

### Organization Tooling

- **[skills](https://github.com/TensorGear/skills)** — 团队复用的 AI coding 与研究工作流 skills。

## Archived

- **[y-maze](https://github.com/TensorGear/y-maze)** — 原独立实验仓库；运行能力已合并到 `animal-platform`。

## Repository Policy

- 自研代码默认放在 TensorGear 私有仓库，默认分支统一为 `main`。
- 数据集、模型权重、视频、虚拟环境、cache 和训练输出不进入 GitHub。
- 论文实验分支必须推送到远端，服务器不得成为唯一副本。
- 第三方项目保留上游 remote，TensorGear 不重复镜像完整上游源码。

## 联系

📍 浙江宁波 · 宁波大学医工院

---

_Ningbo, China · [Ningbo University](https://www.nbu.edu.cn)_
