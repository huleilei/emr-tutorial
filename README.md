
> ⚠️ **项目已停止维护 / Project Retired**
>
> 本项目已于 **2026 年 7 月 5 日** 正式停止维护，不再接收新功能、Bug 修复和安全更新。
>
> This project has been officially retired as of **2026-07-05** and will no longer receive new features, bug fixes, or security updates.
>
> 📌 **替代方案 / Alternative**
>
> 请访问 [火山引擎 EMR 官方文档中心](https://www.volcengine.com/docs/6491) 获取最新的使用指南、示例代码和最佳实践。
>
> For the latest guides, examples, and best practices, please visit the [Volcengine EMR Official Documentation Center](https://www.volcengine.com/docs/6491).
>
> 📦 **代码说明 / Note**
>
> 项目代码将以只读归档形式保留，您仍可 Fork 和参考使用，但不保证安全性和维护支持。
>
> The codebase remains available as a read-only archive. You may fork and reference it, but no security or maintenance support is provided.

---

## 火山EMR简介

火山EMR 提供火山增强的 Hadoop、Spark、Flink、Hive、Presto、Hudi、Iceberg 、Doris/StarRocks、Ray、PyTorch 等大数据与AI 生态组件，100%开源兼容，支持构建 数据湖、湖仓一体、Data for AI 等平台架构。
提供on ECS形态、ON VKE形态，VKE是火山引擎容器服务。EMR中自研湖加速引擎 Proton，存算分离场景下，性能超过存算一体，且成本降低。同时自研向量化执行引擎 Bolt，Spark/Presto计算引擎性能优于开源。
EMR on VKE形态下，提供离线负载与在线业务混部，提高资源利用率；提供Spark、Ray、PyTorch等AI框架和数据预处理工程实践优化等功能。

![img.png](images/emr.png)


## Getting Started
在该工程源码中，提供on ECS形态和on VKE形态下引擎使用示例，便于用于更好的上手。
- **emr-on-ecs**  提供存算分离等场景下的示例代码，参考emr-on-ecs目录下README.md文档进行操作和使用。也可以参考官网[emr-on-ecs](https://www.volcengine.com/docs/6491/1216706) 。
- **emr-on-vke** 提供一些AI和数据分析场景下的示例工程，参考emr-on-vke目录下README.md文档进行操作和使用。也可以参考官网[emr-on-vke](https://www.volcengine.com/docs/6491/1218706) 。


## Security and privacy
This project takes security seriously. 
For vulnerability reporting and supported versions, see [SECURITY.md](SECURITY.md)


## 🤝 支持与反馈
本工程由火山引擎EMR服务团队维护，如果您有反馈、功能想法或希望报告错误，请使用此 GitHub 的[Issues](https://github.com/volcengine/emr-tutorial/issues)，我们将尽最大努力提供支持。
