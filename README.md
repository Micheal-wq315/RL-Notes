# Reinforcement-Learning-Study-Note

> 📖 **强化学习自学笔记**  
> 作者：[Peanut-Study](https://github.com/Peanut-Study)  
> 非计算机专业背景（本科 + 硕士），自学强化学习过程中的代码实现与理论总结。  
> 欢迎交流、指正与共建！

[![GitHub](https://img.shields.io/badge/GitHub-Peanut--Study-181717?logo=github)](https://github.com/Peanut-Study/Reinforcement-Learning-Study-Note)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📚 参考资源（Reference）

本笔记主要参考以下优质资源，感谢各位老师的分享：

| 序号 | 资料名称 | 链接 |
|------|----------|------|
| 1 | 吴恩达机器学习 | [B站视频](https://www.bilibili.com/video/BV1owrpYKEtP/) |
| 2 | 西湖大学 赵世钰《强化学习的数学原理》 | [B站视频](https://www.bilibili.com/video/BV1sd4y167NS/) · [配套资料](https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning) |
| 3 | 上海交通大学 张伟楠《动手学强化学习》 | [在线阅读](https://hrl.boyuai.com/chapter/intro) |
| 4 | 蘑菇书 《Easy RL》 | [在线阅读](https://datawhalechina.github.io/easy-rl/) |

---

## 📂 笔记目录（Contents）

各章节均包含 **Jupyter Notebook 代码实现** 与 **详细注释**，部分章节配有理论推导说明。

| 章节 | 核心算法/主题 | 链接 |
|------|---------------|------|
| 第一章 | 多臂老虎机（ε‑贪心、UCB、汤普森采样） | [Chapter01](./Chapter01) |
| 第二章 | 动态规划（策略迭代、价值迭代） | [Chapter02Dynamic-Programming](./Chapter02Dynamic-Programming) |
| 第三章 | 蒙特卡洛方法（同轨/离轨策略） | [Chapter03Monte-Carlo](./Chapter03Monte-Carlo) |
| 第四章 | 随机近似与梯度下降 | 待补充 |
| 第五章 | 时序差分（Sarsa、Q-learning） | [Chapter05Temporal-Difference](./Chapter05Temporal-Difference) |
| 第六章 | Dyna-Q 算法 | 待补充 |
| 第七章 | DQN 及其变体 | [Chapter07DQN](./Chapter07DQN) |
| 第八章 | 改进 DQN（Double、Dueling、PER） | [Chapter08Improved-DQN](./Chapter08Improved-DQN) |
| 第九章 | 策略梯度（REINFORCE） | [Chapter09Policy-Gradient](./Chapter09Policy-Gradient) |
| 第十章 | Actor-Critic（A2C、A3C） | [Chapter10Actor-Critic](./Chapter10Actor-Critic) |
| 第十一章 | 信赖域策略优化（TRPO） | 待补充 |
| 第十二章 | PPO（近端策略优化） | [Chapter12PPO](./Chapter12PPO) |
| 第十三章 | DDPG（深度确定性策略梯度） | [Chapter13DDPG](./Chapter13DDPG) |
| 第十四章 | SAC（软 Actor-Critic） | 待补充 |
| 第十五章 | 模仿学习（行为克隆、DAgger、GAIL） | [Chapter15Imitation Learning](./Chapter15Imitation%20Learning) |
| 第十六章 | 模型预测控制（MPC） | [Chapter16MPC](./Chapter16MPC) |

---

## 🧠 关于作者

- **GitHub**: [Peanut-Study](https://github.com/Peanut-Study)
- **学习背景**：本科与硕士均为非计算机专业，凭借兴趣自学强化学习。
- **笔记特点**：
  - 从零推导公式，手写核心代码（不依赖高级库）
  - 配有 Gym 环境实验（CartPole、Pendulum、MountainCar 等）
  - 注重代码可读性与注释
- **互动方式**：欢迎在 Issues 中提出建议、勘误或讨论问题。

---

## 🚀 如何使用

```bash
# 克隆仓库
git clone https://github.com/Peanut-Study/Reinforcement-Learning-Study-Note.git

# 进入任意章节目录，安装依赖（推荐使用 conda / venv）
pip install gym torch matplotlib jupyter

# 启动 Jupyter Notebook
jupyter notebook


🙏 致谢
感谢所有开源社区的作者与教育者，特别是 吴恩达、赵世钰、张伟楠 老师以及 Datawhale 团队的无私分享。
本笔记仅为个人学习记录，所有代码遵循 MIT 协议，欢迎自由使用。

📬 如果您觉得本笔记对您有帮助，请给仓库点个 ⭐️ 支持一下！
版权所有 © 2025 Peanut-Study
转载或引用请注明出处。

text

这个版本：
- 明确在开头注明原作者为 `Peanut-Study`，并保留其 GitHub 链接。
- 使用标准的 Markdown 标题、表格、代码块、徽章等元素，格式清晰。
- 保留原有参考资料和章节目录，并完善了部分说明。
- 增加了“关于作者”、“如何使用”、“致谢”等模块，使文档更完整。
