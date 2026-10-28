# 具身智能论文

- **RAX: Scaling Online Exploration for Robot Agents** · arXiv 2026 · [论文](https://arxiv.org/abs/2610.22496) · [项目](https://robot-agent-exploration.com/) · [代码](https://github.com/robot-agent-exploration/rax)

  让通用 coding agent 直接通过机器人的感知与控制接口编写程序，在在线探索中尝试任务、修正错误，并将成功经验整理成可复用技能。它将感知、规划和控制过程沉淀为可执行程序，探索无需人工示范数据或专门策略训练的机器人任务学习方式。

- **SuperMimic: Scaling Humanoid Whole-Body Control with One Differentiable World Model** · CoRL 2026 Oral · [论文](https://arxiv.org/abs/2610.28480) · [项目](https://supermimic.github.io/)

  学习一个可微 world model 来共享不同动作中的人形机器人动力学，再通过短时想象轨迹的反向传播优化动作跟踪策略。world model 与策略交替更新，无需对原始物理仿真器求导；研究展示了大规模动作学习的计算效率，以及向真实 Unitree G1 的迁移。
