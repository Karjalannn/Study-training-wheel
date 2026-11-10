# math-os

数学直博 + 本科课业的**本地优先**学习系统。不含代码，只有规则文档和进度记录。

## 里面有什么

| 路径 | 作用 |
|---|---|
| [`math-os/portal.html`](math-os/portal.html) | 桌面入口页：本周任务 + 四个资源链接 + 三条规矩（可离线打开，勾选存 localStorage） |
| [`math-os/study/RULES.md`](math-os/study/RULES.md) | 监督规则：两套系统分工、周三数、R1–R6 拒绝规则 |
| [`math-os/study/POOL.md`](math-os/study/POOL.md) | 资源池：ACTIVE / CANDIDATE / REJECTED 三态 + 准入 5 条。唯一推荐来源 |
| [`math-os/math-phd-roadmap/`](math-os/math-phd-roadmap/) | 长期路线图：方向用途地图、技能包三档、阶段框架（资源部分已被 POOL 取代） |

## 三条不许违反的约定

1. **只有 `POOL.md` 的 ACTIVE 区能被推荐或导入。** 别处的链接一律视为不存在。
2. **`lookatstudy` 里同时只放一门课**；其余全部进 `study_desk`。
3. **每天先看三数（DUE / NEW / CORE）再决定做什么**，不是先看有什么新东西。

## 运行环境

- DeepSeek Harness，两个插件：`dsh-study-desk`（看板 + 复习队列）、`dsh-plugin-lookatstudy`（课程 + 掌握度）
- 进度数据不在本仓库：看板数据在 `~/.dsh/study-desk/desk.json`，课程数据在 `~/.dsh/lookatstudy-plugin/state.json`
- 本仓库只存**规则与计划**，所以可以直接公开

## 阶段

当前：W6–W12（2026-11 → 2027-01），主押保 GPA / 转专业，课外数学 ≤ 4 h/周。
W13 寒假整体重排：Spivak 转正、雅思启动。
