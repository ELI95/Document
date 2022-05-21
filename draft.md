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
