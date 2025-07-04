# DDPGAgent 最优选课策略

该文件展示了经过训练的Agent在面对所有课程时，所做出的最优出价决策。

### Agent的课程偏好分布
- **最喜欢**: `[7, 3, 11, 9]`
- **中等喜好**: `[24, 17, 13, 2, 14, 10, 4, 20]`
- **不喜欢**: `[19, 5, 18, 21, 6, 23, 12, 8, 0, 15, 1, 16, 22]`

### 详细决策过程

| 课程 ID | 课程类型 | 决策时剩余积分 | Agent决策 (出价) |
|:---:|:---:|:---:|:---:|
| 0 | 不喜欢 | 100 | **34.77** |
| 1 | 不喜欢 | 65.22579956054688 | **29.56** |
| 2 | 中等喜好 | 35.661752700805664 | **0.00** |
| 3 | 最喜欢 | 35.661752700805664 | **0.00** |
| 4 | 中等喜好 | 35.661752700805664 | **0.00** |
| 5 | 不喜欢 | 35.661752700805664 | **0.00** |
| 6 | 不喜欢 | 35.661752700805664 | **0.00** |
| 7 | 最喜欢 | 35.661752700805664 | **34.03** |
| 8 | 不喜欢 | 1.6346187591552734 | **0.00** |
| 9 | 最喜欢 | 1.6346187591552734 | **0.75** |
| 10 | 中等喜好 | 0.8803398609161377 | **0.00** |
| 11 | 最喜欢 | 0.8803398609161377 | **0.00** |
| 12 | 不喜欢 | 0.8803398609161377 | **0.00** |
| 13 | 中等喜好 | 0.8803398609161377 | **0.00** |
| 14 | 中等喜好 | 0.8803398609161377 | **0.00** |
| 15 | 不喜欢 | 0.8803398609161377 | **0.07** |
| 16 | 不喜欢 | 0.8056686520576477 | **0.04** |
| 17 | 中等喜好 | 0.764583170413971 | **0.00** |
| 18 | 不喜欢 | 0.764583170413971 | **0.02** |
| 19 | 不喜欢 | 0.7486270070075989 | **0.01** |
| 20 | 中等喜好 | 0.7385568022727966 | **0.00** |
| 21 | 不喜欢 | 0.7385568022727966 | **0.01** |
| 22 | 不喜欢 | 0.7304326891899109 | **0.01** |
| 23 | 不喜欢 | 0.72161865234375 | **0.01** |
| 24 | 中等喜好 | 0.7109196186065674 | **0.00** |
