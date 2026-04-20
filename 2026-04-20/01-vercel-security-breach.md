# Vercel 确认数据泄露：黑客声称正在出售被盗数据

**日期**: 2026-04-20
**时间**: 19:00
**来源**: BleepingComputer
**标签**: #安全 #Vercel #数据泄露

## 🔗 原文链接
- [Vercel confirms breach as hackers claim to be selling stolen data](https://www.bleepingcomputer.com/news/security/vercel-confirms-breach-as-hackers-claim-to-be-selling-stolen-data/)

## 📝 摘要
云开发平台 Vercel 披露安全事件，攻击者声称已入侵其系统并正在出售被盗数据。事件源于第三方 AI 工具 Context.ai 的 Google Workspace OAuth 应用被入侵，导致 Vercel 员工账户被攻破。

## 💡 关键点
- 攻击者通过入侵的 Google Workspace 账户访问了 Vercel 内部系统
- 泄露了约 580 条 Vercel 员工信息记录
- 未被标记为"敏感"的環境变量被攻击者进一步枚举利用
- Vercel CEO 透露赎金要求为 200 万美元
- Next.js、Turbopack 等开源项目被确认安全

## 📈 影响分析
这是又一起针对开发者工具平台供应链攻击的事件。Vercel 建议用户：
- 审查所有环境变量
- 启用敏感环境变量功能
- 如有需要轮换密钥

此类事件再次提醒开发者：即使是看似安全的平台，也可能存在第三方依赖的安全隐患。

---
*由科技新闻收集器生成*
