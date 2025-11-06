---
description: 将用户布置的任务集群拆分为可并行执行的任务组，然后交给工作 Agent 并行完成
argument-hint: "<task_descriptions>"
model: haiku
---

使用 `complexMissionManager:task-assigner` 来对 `task_descriptions` 所描述的大型任务组的分析、拆解、执行以及最终汇报