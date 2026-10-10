<p align="center"><img src="assets/ssrobotics-logo.jpg" alt="SSRobotics — original logo by SSRobotic" width="240"></p>

<h1 align="center">💾 Datasets & Demonstrations</h1>
<p align="center"><b>SSRobotics · Source Code Collection</b></p>

<p align="center">
  <a href="https://ssrobotic.github.io/humanoid-robot-hub/"><img src="https://img.shields.io/badge/Resources-5-f28c28?style=flat-square" alt="5 curated resources"></a>
  <a href="https://ssrobotic.github.io/humanoid-robot-hub/"><img src="https://img.shields.io/badge/Language-TH_%2F_EN-555555?style=flat-square" alt="Thai and English"></a>
  <a href="https://github.com/SSRobotic/humanoid-robot-hub/blob/main/CREDITS.md"><img src="https://img.shields.io/badge/Original_sources-Credited-555555?style=flat-square" alt="Original authors credited"></a>
</p>


**Part of [Humanoid Robot Hub](https://github.com/SSRobotic/humanoid-robot-hub)** · [🔎 Search all resources](https://ssrobotic.github.io/humanoid-robot-hub/)

Robotics dataset catalogs, data formats and training data utilities.

คลัง Dataset หุ่นยนต์ รูปแบบข้อมูล และเครื่องมือจัดเตรียมข้อมูลฝึก

Curated by **SSRobotic — Robotics Engineer & Open-source Curator**. This repository is a focused resource directory and engineering guide. Linked SDKs, models and research implementations belong to their original creators.

## 🗂️ Resource directory

| Resource | What it provides | Keywords | Original source |
| --- | --- | --- | --- |
| [LeRobot](https://github.com/huggingface/lerobot) | Robot learning tools, datasets and policies. A supporting embodied AI resource; hardware support is project-specific. | Imitation learning, Datasets, Python | [huggingface](https://github.com/huggingface/lerobot) |
| [X-Humanoid Training Toolchain](https://github.com/Open-X-Humanoid/x-humanoid-training-toolchain) | Tools connecting TienKung / RoboMIND workflows with LeRobot. | TienKung, RoboMIND, LeRobot | [Open-X-Humanoid](https://github.com/Open-X-Humanoid/x-humanoid-training-toolchain) |
| [Open X-Embodiment](https://github.com/google-deepmind/open_x_embodiment) | Cross-embodiment robot dataset resources and supporting tooling. | Datasets, Cross-embodiment, Robotics | [google-deepmind](https://github.com/google-deepmind/open_x_embodiment) |
| [RoboMIND Dataset](https://huggingface.co/datasets/x-humanoid-robomind/RoboMIND) | Multi-embodiment demonstration data, including TienKung. See the dataset card for access conditions. | RoboMIND, Demonstrations, TienKung | [X-Humanoid / RoboMIND](https://huggingface.co/datasets/x-humanoid-robomind/RoboMIND) |
| [ArtVIP Assets](https://huggingface.co/datasets/X-Humanoid/ArtVIP) | Articulated-object digital-twin datasets and scene assets from X-Humanoid. | Digital twin, USD, Assets | [X-Humanoid](https://huggingface.co/datasets/X-Humanoid/ArtVIP) |

## 📦 Code & models in this repository

**12 tracked upstream files** — เปิดโฟลเดอร์ด้านล่างเพื่อดูโค้ดจริง โมเดล และตัวอย่างต้นฉบับ

| Project files | Files | Pinned source | License / notices |
| --- | ---: | --- | --- |
| [google-deepmind/open_x_embodiment](projects/open_x_embodiment) | 12 | [`9eeb68b989ef`](https://github.com/google-deepmind/open_x_embodiment/tree/9eeb68b989efbcf474e8fb9019e01d02b962a604) | [LICENSE](projects/open_x_embodiment/LICENSE) |

[Source manifest](source-manifest.json) records commits, file counts, Git LFS pointers and external submodules. [Per-file manifests](source-manifests/) record original Git blob hashes. `projects/` keeps upstream code, README files, licenses and notices; SSRobotics supplies the organization and guides.

```bash
git clone --depth 1 https://github.com/SSRobotic/humanoid-datasets.git
cd humanoid-datasets
```

The Open X-Embodiment folder contains real dataset inspection/loading notebooks and documentation. Raw robot datasets are downloaded separately from the original providers; each dataset retains its own access conditions and license.

## 🚀 Start here

1. Select a dataset that matches the embodiment, task and sensing setup.
2. Review its access conditions, license, formats and train / evaluation split.
3. Inspect a small documented example and preserve task / frame metadata during conversion.

Read the [engineering guide](GUIDE.md) for a practical selection checklist. [resources.json](resources.json) contains the structured entries.

## 🔗 Explore the ecosystem

<details>
<summary>🌐 Browse all 14 categories</summary>

[🦾 Models & URDF](https://github.com/SSRobotic/humanoid-models) · [🌐 Simulation](https://github.com/SSRobotic/humanoid-simulation) · [🧠 Robot Learning](https://github.com/SSRobotic/humanoid-robot-learning) · [⚙️ Whole-body Control](https://github.com/SSRobotic/humanoid-whole-body-control) · [👁️ Vision & 3D Perception](https://github.com/SSRobotic/humanoid-vision) · [🤏 Manipulation & Planning](https://github.com/SSRobotic/humanoid-manipulation) · [🎮 Teleoperation](https://github.com/SSRobotic/humanoid-teleoperation) · [💾 Datasets & Demonstrations](https://github.com/SSRobotic/humanoid-datasets) · [💬 Vision-Language-Action](https://github.com/SSRobotic/humanoid-vla) · [🔌 Hardware & SDKs](https://github.com/SSRobotic/humanoid-hardware-sdks) · [📡 ROS & Integration](https://github.com/SSRobotic/humanoid-ros2) · [📚 Research & Benchmarks](https://github.com/SSRobotic/humanoid-research) · [🟢 Isaac Sim & Isaac Lab](https://github.com/SSRobotic/humanoid-isaac-sim) · [🧮 Robotics Algorithms](https://github.com/SSRobotic/humanoid-algorithms)

</details>

[🏠 Main Hub](https://github.com/SSRobotic/humanoid-robot-hub) · [🤖 Profile](https://github.com/SSRobotic)

## 🙌 Help this collection grow

⭐ [Star the Hub](https://github.com/SSRobotic/humanoid-robot-hub) · 👤 [Follow SSRobotic](https://github.com/SSRobotic) · 💡 [Suggest a resource](https://github.com/SSRobotic/humanoid-robot-hub/issues/new/choose)

Contribute accurate descriptions and original source links through the [Hub contribution guide](https://github.com/SSRobotic/humanoid-robot-hub/blob/main/CONTRIBUTING.md). Source terms, model compatibility and dataset access conditions remain with each upstream project.
