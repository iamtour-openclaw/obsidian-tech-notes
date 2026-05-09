# "Dirty Frag" 漏洞曝光：几乎所有 Linux 发行版受影响

**日期**: 2026-05-09
**时间**: 19:00
**来源**: Openwall / The Verge
**标签**: #Linux #安全 #漏洞 #LPE #CVE

## 🔗 原文链接
- [Dirty Frag: Universal Linux LPE](https://www.openwall.com/lists/oss-security/2026/05/07/8)
- [The Verge: All Linux distros affected](https://www.theverge.com/tech)

## 📝 摘要
安全研究人员 Hyunwoo Kim 披露了名为"Dirty Frag"的通用 Linux 本地提权（LPE）漏洞（CVE-2026-43284）。该漏洞允许本地用户在几乎所有 Linux 发行版上获取 root 权限。由于保密协议已被打破，目前不存在补丁或完整的 CVE 信息。这是继上周"Copy Fail"漏洞后又一严重 Linux 内核安全事件，两个漏洞仅相隔一周被发现。

## 💡 关键点
- "Dirty Frag"（CVE-2026-43284）是影响所有 Linux 发行版的通用 LPE 漏洞
- 允许本地用户获取 root 权限，危害极高
- 由于保密协议已被打破，目前没有可用的补丁
- 距上周的"Copy Fail"漏洞（CVE-2026-3141）仅一周
- Linux 内核安全正面临密集的漏洞披露期

## 📈 影响分析
连续两周出现严重的 Linux 内核 LPE 漏洞令人担忧。Dirty Frag 与 Copy Fail 的组合意味着几乎所有 Linux 服务器都可能面临本地提权风险。对于云服务商和企业 IT 部门而言，需要紧急评估这两组漏洞的影响，并关注上游内核的补丁发布。事件也引发了关于 Linux 内核安全审查流程和漏洞披露政策的讨论。
---
*由科技新闻收集器生成*
