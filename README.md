> [!IMPORTANT]
> 🌟 Stay up to date at [opendrivelab.com](https://opendrivelab.com/#news)!

<div id="top" align="center">

<img src="https://opendrivelab.github.io/Nexus/resources/NEXUS-text.gif" alt="Image description" width="70%">

# Decoupled Diffusion Sparks Adaptive Scene Generation

<!--
**Revive driving scene understanding by delving into the embodiment philosophy**-->

<a href="http://arxiv.org/abs/2504.10485"><img src="https://img.shields.io/badge/arXiv-Paper-<color>"></a>
<a href="https://opendrivelab.com/Nexus"><img src="https://img.shields.io/badge/Project-Page-orange"></a>
<a href="README.md">
  <img alt="Nexus: v1.0" src="https://img.shields.io/badge/Nexus-v1.0-blueviolet"/>
</a>
<a href="#license-and-citation">
  <img alt="License: Apache2.0" src="https://img.shields.io/badge/license-Apache%202.0-blue.svg"/>
</a>

<!--
<img src="https://opendrivelab.github.io/Nexus/resources/teaser.png" alt="Image description" width="70%">
-->

</div>





<div style="display: flex; justify-content: center; align-items: center; gap: 1%;">

  <img src="https://opendrivelab.github.io/Nexus/resources/main_vis1.gif" width="24%" alt="Video 1">

  <img src="https://opendrivelab.github.io/Nexus/resources/main_vis2.gif" width="24%" alt="Video 2">

  <img src="https://opendrivelab.github.io/Nexus/resources/main_vis3.gif" width="24%" alt="Video 3">

  <img src="https://opendrivelab.github.io/Nexus/resources/main_vis4.gif" width="24%" alt="Video 4">

</div>

> [Yunsong Zhou](https://zhouyunsong.github.io/), [Naisheng Ye](https://Y-vic.github.io/), William Ljungbergh, Tianyu Li, _et al._
> - :mailbox_with_mail: Primary contact: [Yunsong Zhou]((https://zhouyunsong-sjtu.github.io/)) ( zhouyunsong2017@gmail.com ) 


## Highlights <a name="highlights"></a>

:fire: **Nexus** is a **noise-decoupled** prediction pipeline designed for adaptive driving scene generation, ensuring both `timely reaction⏲️` and `goal-directed control🥅`.

:star2: Nexus can generate realistic `safety-critical` driving scenarios by flexibly controlling the future state of a scene, with the assistance of NeRF.


<div style="display: flex; justify-content: center; align-items: center; gap: 1%;">

  <img src="https://opendrivelab.github.io/Nexus/resources/nerf-1.gif" width="24%" alt="Video 1">

  <img src="https://opendrivelab.github.io/Nexus/resources/nerf-2.gif" width="24%" alt="Video 2">

  <img src="https://opendrivelab.github.io/Nexus/resources/nerf-5.gif" width="24%" alt="Video 3">

  <img src="https://opendrivelab.github.io/Nexus/resources/nerf-4.gif" width="24%" alt="Video 4">

</div>


## News <a name="news"></a>

- `[2024/04]` Nexus [paper](https://arxiv.org/abs/2504.10485) released.
- `[2025/04]` Nexus code and data initially released.

## Table of Contents

1. [Highlights](#highlights)
2. [News](#news)
3. [TODO List](#todo)
4. [Getting Started](#get-start)
5. [Dataset](#dataset)
6. [License and Citation](#license-and-citation)
7. [Related Resources](#resources)

## TODO List <a name="todo"></a>


- [ ] Guidance tutorial
- [x] Training code
- [x] Nexus & checkpoint
- [x] Initial repo & paper


## Getting Started <a name="get-start"></a>
- [Installation](docs/install.md)
- [Try Our Demo 🔥](docs/demo.md)
- [Prepare Dataset](docs/prepare_dataset.md)
- [Train and Eval](docs/train_eval.md)

## Dataset <a name="dataset"></a>

<img src="https://opendrivelab.github.io/Nexus/resources/nexus-data.png" alt="Image description" width="100%">

Nexus-Data is induced from real-world scenarios, in which we can obtain real-world map topology and layout. It also includes hazardous driving behaviors through interactions introduced by adversarial traffic generation. The safety-critical scenarios (on nuPlan dataset) can be obtained through this 🔗[data link](https://huggingface.co/datasets/OpenDriveLab-org/Nexus-data/tree/main).




## License and Citation

All assets and code in this repository are under the [Apache 2.0 license](./LICENSE) unless specified otherwise. The data is under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Please consider citing our paper and project if they help your research.

```BibTeX
@inproceedings{zhou2025nexus,
  title={Decoupled Diffusion Sparks Adaptive Scene Generation},
  author={Zhou, Yunsong and Ye, Naisheng and Ljungbergh, William and Li, Tianyu and Yang, Jiazhi and Yang, Zetong and Zhu, Hongzi and Petersson, Christoffer and Li, Hongyang},
  booktitle={ICCV},
  year={2025}
}
```

## Related Resources <a name="resources"></a>

We acknowledge all the open-source contributors for the following projects to make this work possible:

- [GUMP](https://github.com/HorizonRobotics/GUMP) | [DiffusionPlanner](https://github.com/ZhengYinan-AIR/Diffusion-Planner)


<a href="https://twitter.com/OpenDriveLab" target="_blank">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/OpenDriveLab?style=social&color=brightgreen&logo=twitter" />
  </a>

- [SimGen](https://github.com/OpenDriveLab/DriveAGI) | [Vista](https://github.com/OpenDriveLab/Vista) | [Centaur](https://github.com/OpenDriveLab/Centaur)
- [MTGS](https://github.com/OpenDriveLab/MTGS) | [OpenLane-V2](https://github.com/OpenDriveLab/OpenLane-V2) |  [OpenScene](https://github.com/OpenDriveLab/OpenScene)

