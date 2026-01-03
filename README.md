# CoTrip-Introduction
`CoTrip`（Collaborative Trip）是一个多人协同旅行规划系统，支持行程规划、费用记账、社区分享等功能。

不止于项目本身的“协作”，项目开发也是由我们Ⅲ完成的。

**Important**——两位团队成员：[Benjaamiiin11](https://github.com/Benjaamiiin11)、[cpanda5](https://github.com/cpanda5)。

演示地址：https://cotripplus.netlify.app/

测试账号：

| 账号  | 密码     |
| ----- | -------- |
| user1 | 12345aB# |
| user2 | 12345aB# |
| user3 | 12345aB# |

> ps：当前有个bug暂时没修，见谅——头像、图片无法正确显示的问题（但是开发环境是能正确显示的）
>
> 原因：HTTPS不能请求HTTP，开发时用的HTTP的Minio地址，上线后没改过这个逻辑……所以……
>
> 暂时先不去改的原因也很简单，因为要把数据库中的已有数据都要对应修改了。后续要改的话直接对接腾讯云的对象存储比较方便……但是现在没空改代码了（找工作ing……）

前后端代码仓库：[CoTrip-frontend](https://github.com/Yukinoshita52/CoTrip-frontend)、[CoTrip-backend](https://github.com/Yukinoshita52/CoTrip-backend)

从需求分析，到数据库设计，再到接口约定，再到实际开发、上线。该项目的全流程由我们三人完成。

愿你我人生旅途不再孤单，有人陪你一起旅行。

# 技术栈使用

## 前端

- **前端框架**: Vue 3 + TypeScript
- **UI 组件库**: Element Plus
- **路由管理**: Vue Router 4
- **状态管理**: Pinia
- **构建工具**: Vite
- **HTTP 客户端**: Axios
- **日期处理**: Day.js

## 后端

- **框架**: Spring Boot 3.x
- **数据库**: MySQL 8.0
- **缓存**: Redis 7.x
- **文件存储**: MinIO
- **ORM**: MyBatis Plus
- **文档**: SpringDoc (Swagger)
- **构建工具**: Maven

# Thank you team workers

**Important**：再次鸣谢两位团队成员：[Benjaamiiin11](https://github.com/Benjaamiiin11)、[cpanda5](https://github.com/cpanda5)。

队长Benjaamiiin11是对这个项目最为负责的，从项目开始到结束始终把握进度，对于前端ui有着惊人的执着所以和cursor对话了几百轮换来了如今美妙的界面^^。是的，前端全程由ai编辑器生成，我的话一开始还比较老实地去复习Vue，学了一遍发现没啥用，干脆上手吧，搓搓表格啥的进度太慢了，于是也入坑ai工具（trae、kiro、cursor，主要是前两个免费额度高）

cpanda5人狠话不多，自己部分的内容早早完成了，后续帮助我们修修补补。

