# 诸葛远鹏

Web 前端 / 全栈开发，主要使用 TypeScript、React、Next.js 和 Node.js。

做过企业官网、商户菜单管理小程序和 AI 应用，参与需求梳理、页面与接口开发、测试和部署。关注具体业务流程，也喜欢把个人想法做成可以使用的小工具。

## 业务实践

- **码成仝官网**：负责官网前后端开发与内容管理，接入 Payload CMS、PostgreSQL 和表单审核流程；实现站内文档检索问答，处理模型接口的参数校验、限流与超时。
- **Kith Inn / 街坊味**：参与商户菜单管理小程序的需求梳理、原型设计、开发与接口联调，覆盖菜品库、周菜单编排、历史菜单复用和菜单文字复制。

## 公开项目

### [AI 狼人杀 · 同步观战](https://github.com/miyin-derick/langrensha)

基于开源项目改造的 AI 狼人杀观战应用，支持 12 个 AI 玩家对局和远程同步观战。

- 我的改造：Supabase 房间同步、房主与观众权限区分、多模型接入、对局信息与记忆整理，以及 Vercel 部署。
- 技术：React · TypeScript · Vite · Supabase · Vercel API Routes
- [演示入口](https://feature-watch-together.vercel.app) · [实现说明与运行方式](https://github.com/miyin-derick/langrensha#readme)

### [微信 MCP · 图片处理与监听集成](https://github.com/miyin-derick/mcp-wechat-server-integrated)

基于上游微信 MCP 服务扩展图片处理，并提供连接 OpenClaw 的常驻监听示例。

- 我的扩展：图片媒体信息、下载与解密工具；唤醒 / 休眠控制、图片问答转发及 macOS launchd 示例。
- 技术：TypeScript · Bun · MCP SDK · Zod
- [与上游的关系及新增内容](https://github.com/miyin-derick/mcp-wechat-server-integrated#readme)

## 常用技术

- 前端：TypeScript、React、Next.js、Taro
- 服务端与数据：Node.js、PostgreSQL、Payload CMS
- 测试：Vitest、Playwright
