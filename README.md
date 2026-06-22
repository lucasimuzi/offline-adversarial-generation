# Offline Adversarial Generation（离线对抗场景生成）

> 仓库用于系统性跟踪自动驾驶对抗场景生成技术，包括对抗样本生成、闭环仿真、场景多样性增强等方向。
> **生成模型**: MiniMax-M3.0（2026-06-22 切换；历史文档为 M2.7）
> **最后更新**: 2026-06-22（迁移 CompoSIA + 推送 06-12~20 日报）

## 技术方向
- **对抗样本生成**：物理对抗Patch、纹理扰动、CAE/VAE生成对抗噪声
- **闭环仿真**：Safety verification、Coverage-guided fuzzing、Scene replanning
- **场景多样性增强**：Distribution shift detection、Corner case挖掘、3DGS场景生成
- **组合式视频生成**：解耦控制（场景结构 + 对象身份 + 自车动作），单参考图像身份替换（姿态无关）

## 目录结构
```
papers/         # 论文索引（papers.md）+ 每篇洞察文档
  ├── papers.md
  └── CompoSIA/insight.md    # 2026-06-22 迁移自 world-model
codes/          # 开源项目索引（codes.md）+ 每项目分析文档
daily_reports/  # 每日技术洞察报告（YYYY-MM-DD.md）
deep_dive/      # 专题深度报告（按专题建二级子目录）
```

## 2026-06-22 更新说明
- 新增 `papers/CompoSIA/insight.md`（从 world-model 仓迁移）
- 新增 `papers/papers.md` 完整索引
- 推送 `daily_reports/daily_report_2026-06-12.md` ~ `2026-06-20.md`（9 个日报，cron 已生成但未推）
- 模型标记 M2.7 → M3.0

## 模型说明
本仓库技术洞察文档默认由 **MiniMax-M3.0** 模型生成（2026-06-08 起从 M2.7 切换）。明确要求使用 deepseek-chat 时会另行标注。

---

*Last updated: 2026-06-22*
