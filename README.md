# superagent 本地工作区

这是 dsh-superagent 的本地执行根目录。工单（Ticket）会在这里以 git worktree 的方式
检出独立目录，由执行器 Session 完成修改、提交、推送分支并开 PR。

- 想让它管什么，就往这个目录里放什么。
- 每个工单一个分支：agent/<工单短名>，改动以 PR 形式回到 agent-inbox 仓库审阅。
- 本仓库 origin 指向私有仓库 xxuuzhen-agent/agent-inbox（仅作备份与审阅通道）。

hello
