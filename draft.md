https://github.tesla.com/Factory-Software/fx-factory
https://github.tesla.cn/ITApp/dots

kafka
unit test

DTO (Data Transfer Object)


- 开发
包管理
代码结构
本地开发环境
TryMOS使用
设计方案 - 定义接口 - 生成open api yaml - 编码实现
代码自动生成

env
  - ENG
  - STG
  - PRD

service
  - abt: Aftersale Breakpoint Tracking


dots/quality/audit
- procedure
  - request -> Route -> Handler -> reqCtx.Find(&logic) -> BizLogic -> DataLayer -> db

- concept
  - BizLogic
  - DataLayer

lines
common framework

app
inject
feature
invoke
provide
outbound

Branch: Generate branch on JIRA
Commits:
Make sure every commit contains card number
Squash to one commit per PR unless you make every commit meaningful (git rebase -i)

pick (or p): use commit
reword (or r): use commit, but edit the commit message
edit (or e): use commit, but stop for amending
squash (or s): use commit, but meld into previous commit
