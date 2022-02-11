---
sidebar_position: 1
id: my-home-doc
slug: /
---

# 👋 歡迎 !

Connext 是 L2 以太坊的互操作性协议。

您可以使用 Connext 跨链和/或汇总发送价值交易或调用数据。 与大多数其他互操作性系统不同，Connext *无需*引入任何新的信任假设或外部验证器即可实现这一点。

请注意，当前版本的 Connext 不能用于在链之间传递任意事件数据（即向链 B 证明链 A 上发生了某些事情），因为这不能在 evm 中以信任最小化的方式完成，除非产生 1 周 现有卷帘桥的出口窗口。

这意味着不支持将代币从链 A 迁移到链 B 之类的情况 - 您只能在链上已经存在的流动性上进行交换/交易。

## 内容

这些文档包含用于集成 Connext 和流动性提供者的开发人员的信息。如果您有兴趣为系统的开发做出贡献，请查看我们的 [核心实现 repo](https://github.com/connext/nxtp) 中的自述文件。

#### [快速启动](./Integration/QuickStart/setup)

想立即开始在您的 dApp 中进行跨链交互吗？我们在快速入门指南中逐步介绍了 E2E 集成流程。

#### [系统概述](./Integration/SystemOverview/faq)

系统概述部分涵盖了有关跨链互操作性以及 **nxtp**（Connext 底层协议）如何工作的高级信息。

#### [指南](./developers/getting-started)

更多指南即将推出！我们将介绍常见的工作流程，例如跨链调用合约和 UX 提示！

#### [API 参考](./APIReference/sdkAPI)

API 参考也即将推出！

---

不知道从哪里开始？来我们的 [社区聊天](https://chat.connext.network) 打个招呼吧！
