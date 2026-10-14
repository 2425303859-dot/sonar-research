# sonar-research｜声呐研究记录

声呐图像目标检测与分割的论文阅读、代码复现和实验记录。

本仓库作为研究进度入口，保存阅读笔记、每周总结、项目说明与实验依据。代码项目通过下方链接进入。

## 最新进度

更新日期：2026-10-14

| 内容 | 当前状态 | 入口 |
| --- | --- | --- |
| FLSSNet 论文 | 已有辅助整理稿，待本人精读、修正并补充理解；尚未复现 | [阅读笔记](papers/2025-FLSSNet.md) |
| 声呐检测入门示例 | 已有代码及历史运行报告；报告对应合成数据，本次未重新运行 | [项目说明与结果](projects/sonar-detection-demo.md) |
| 声呐仿真与处理 | 已有独立仓库，运行情况待本人核实 | [原项目](https://github.com/2425303859-dot/first-changku) |
| SCTD2 U-Net 分割项目 | 待定位代码、日志与真实数据，暂不登记为复现完成 | [待办清单](docs/next-steps.md) |
| 本周汇报 | 建档中；当前只登记 1 篇论文辅助笔记，尚未达到每周 2～3 篇目标 | [截至 10 月 14 日的周报](weekly/2026-10-14.md) |

## 论文阅读

| 年份 | 论文 | 任务 | 笔记 | 状态 |
| --- | --- | --- | --- | --- |
| 2025 | [CNN–Transformer Hybrid Architecture for Underwater Sonar Image Segmentation](https://doi.org/10.3390/rs17040707) | 前视声呐显著目标分割 | [FLSSNet](papers/2025-FLSSNet.md) | 辅助整理，待本人精读 |

## 每周更新方式

1. 阅读 2～3 篇相关论文，为每篇创建阅读笔记，注明原文和代码来源。
2. 推进复现，记录环境、数据划分、配置、运行步骤与问题。
3. 保存指标、训练曲线、预测图和失败案例，区分真实数据与合成数据。
4. 更新周报及本页进度，组会按“问题—方法—结果—思考—下一步”讲解。

阅读数量与完整复现数量分别记录；跨周实验如实写明当前阶段。

## 常用入口

- [论文笔记模板](templates/paper-note.md)
- [每周总结模板](templates/weekly-report.md)
- [实验记录模板](templates/experiment-record.md)
- [GitHub 更新操作指南](docs/github-workflow.md)
- [近期待办](docs/next-steps.md)
- [结果目录说明](results/README.md)
- [汇报材料说明](presentations/README.md)

## 记录原则

论文中的结果、已有项目的历史结果和本周新运行结果分别标注。辅助生成的笔记须由本人核对后再用于汇报，不把未验证内容写成已掌握或已复现。
