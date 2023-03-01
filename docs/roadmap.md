# 开发进度

## α 开发阶段

### `0.1.x`

- server 采用较稳定的 GraphQL 和 TypeORM 实践方式。
- web 和 android 实现日程、项目、行动和日记的 CRUD。
- 设备与服务器的数据同步算法采用全量传输同步方式。

### 2021.06.17

- day-primer-mobile 更名为 day-primer-android，采用 Java 语言开发。
- 目前开发的重心是 day-primer-server、day-primer-web 和 day-primer-android，重点实现本地缓存和数据同步。
- 暂停其他分支项目的开发。

### 2020.12.17

采用 GraphQL 接口规范和 Vercel 平台后的第一个版本。

- BACKEND [Journal] 更新和删除
- WEB [Journal] 分页浏览、新建和编辑

## 原始设计阶段

### 2020.7.30 `M1`

- `core` 使用 KOA 和 Commander 支持 API 端点。
- `cli`, `core`, `web` 支持创建用户和用户登陆，使用凭证进行鉴权；用户登陆支持本地和远程方式。

### 2020.7.30

DayPrimer 抛弃文档驱动开发，开始采用敏捷开发。

> “如果文档驱动开发，不知要猴年马月才能动工。”
> 毕竟我不想花三年时间得到 4732 个 bug。

### 2020.1.20

- “Phase”更名为“DayPrimer”。

### 2020.1.7

- Phase 正式进入需求分析与设计阶段，采用“文档驱动开发”。
- 否决了采用 blessed 创建用户界面的想法。
- 主力编写 phase-docs，开始设计各端用户界面。
