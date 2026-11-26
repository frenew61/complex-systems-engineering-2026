# complex-systems-engineering-2026

复杂系统工程（Complex Systems Engineering）课程作业仓库。

- GitHub Pages 入口：**https://frenew61.github.io/complex-systems-engineering-2026/**
- 仓库可见性：Public · 默认分支：`main`
- Pages 发布来源：`main / (root)`，入口文件为根目录 `index.html`

## 作业提交（按日期分组）

| 日期 | 作业 | 说明 | 链接 |
|---|---|---|---|
| 2026-11-11 | 小组讨论：六层层级拆解 | 所选系统为「面向高级别自动驾驶的线控底盘平台」，定位 Systems 层，补全任务—体系—整机—系统—子系统—模块 | [submissions/2026-11-11-group-discussion/by-wire-chassis-platform.md](submissions/2026-11-11-group-discussion/by-wire-chassis-platform.md) |
| 2026-11-15 | 小组作业2：BRS + StRS | 依据 ISO/IEC/IEEE 29148:2018 表4-1、表4-5 输出业务需求与相关方需求规格说明，含 ConOps / OpsCon / 相关方列表 | [根目录 index.html](index.html)（Pages 入口） · [归档目录](submissions/2026-11-15-assignment2/) |
| 2026-11-20 | 小组作业3：SyRS + 初始架构 + 控制结构框图 | 依据 ISO/IEC/IEEE 29148:2018 表5-1 输出系统需求规格书、初始系统架构、系统控制结构框图与安全需求/安全架构 | [submissions/2026-11-20-assignment3/index.html](submissions/2026-11-20-assignment3/index.html) · [说明文档](submissions/2026-11-20-assignment3/by-wire-chassis-platform-assignment3.md) |
| 2026-11-26 | 小组作业4：场景分层 + ODC + 风险分析 | 场景分层与要素梳理、运行设计条件（ODD / 系统状态 / 人员状态）、典型场景详细论述、安全风险分析与风险场景列表 | [submissions/2026-11-26-assignment4/index.html](submissions/2026-11-26-assignment4/index.html) · [说明文档](submissions/2026-11-26-assignment4/by-wire-chassis-platform-assignment4.md) |

## 目录结构

```
.
├── index.html                                  # GitHub Pages 入口（小组作业2：BRS/StRS）
├── README.md
└── submissions/
    ├── 2026-11-11-group-discussion/
    │   └── by-wire-chassis-platform.md         # 六层层级拆解
    ├── 2026-11-15-assignment2/
    │   └── index.html                          # 跳转到根目录作业页
    ├── 2026-11-20-assignment3/
    │   ├── index.html                          # SyRS / 初始架构 / 控制结构框图（内嵌 SVG）
    │   └── by-wire-chassis-platform-assignment3.md  # 作业3 说明文档
    └── 2026-11-26-assignment4/
        ├── index.html                          # 场景分层 / ODC / 典型场景 / 风险列表（内嵌 SVG）
        └── by-wire-chassis-platform-assignment4.md  # 作业4 说明文档
```

## 说明

- 根目录 `index.html` 为课程明确要求的 Pages 入口文件，请勿移动。
- 历史作业按提交日期归档在 `submissions/YYYY-MM-DD-<topic>/` 目录下。
