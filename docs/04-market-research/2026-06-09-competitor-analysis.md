# ForgeFlow 竞品分析

_Date: 2026-06-09_

## 结论

澳洲市场里已经有不少接近 ForgeFlow 方向的产品，但大多是把需求拆开覆盖，而不是一个轻量工具同时解决：

- 现场进度 tracking
- 缺料 / 补料提醒
- 库存管理
- 客户追工期

换句话说，**“有解决方案，但没有完全贴合你们这个 workflow 的单一产品”**。现有产品更像 ERP、MRP、job management 或 inventory system 的组合。

## 竞品概览

| 产品 | 主要定位 | 覆盖点 | 和 ForgeFlow 的关系 |
| --- | --- | --- | --- |
| JAQ | 澳洲 workshop/job management | quote、job、labour、materials、purchases、stock、despatch、job costs | 最接近车间工作流，但偏内部管理，不是客户追工期型产品 |
| Nexvia Production Portal | 生产/项目协同 | production portal、团队协作、time tracking、scheduling、inventory management | 更偏项目型生产协同，适合中大型流程管理 |
| Wiise | ERP / job & project costing / manufacturing | jobs & projects、inventory、supply chain、manufacturing jobs、warehouse operations | 功能很全，但更重、更像后台系统 |
| Fishbowl Manufacturing | 库存与生产管理 | inventory control、production planning、order tracking、reorder quantity、work orders、BOM | 对材料和生产很强，但客户可视化较弱 |
| BSimple | 库存 + customer ordering portal | inventory、automatic PO、customer ordering portal、order status | 客户 portal 很接近，但制造执行深度不够 |

## 逐个分析

### 1. JAQ

JAQ 是澳洲本土的 workshop job management 软件，官方主打 job、materials、purchases、stock、despatch、job costs 这些能力。它的贴合点在于，它确实理解“车间里一个 job 从报价到完工”的链路。

适合的场景：

- workshop / fabrication / job-based manufacturing
- 内部 job tracking
- 材料和采购关联

不足：

- 更偏内部运营，不是面向客户的追工期工具
- 没有把“客户实时看进度”作为明显核心卖点

### 2. Nexvia Production Portal

Nexvia 的 Production Portal 强调生产团队和 office 团队协作、time tracking、scheduling、inventory management 和 project visibility。它把“现场”和“办公室”连起来这一点做得比较明显。

适合的场景：

- 生产计划和团队协同
- 需要 portal 的项目型业务
- 想把 production 和 office 放到一个系统里

不足：

- 更偏 construction / project management 语境
- 对你说的“缺料一键回报、客户直接追工期”未必是核心交付点

### 3. Wiise

Wiise 更像完整 ERP。它覆盖 projects & job costing、inventory、manufacturing jobs、warehouse operations、supply chain 等模块，适合需要统一后台的大公司。

适合的场景：

- 后台统一管理
- 预算、成本、供应链、仓储一体化
- 制造和项目并行的公司

不足：

- 体量偏重，实施成本高
- 对一线 workshop 的即时补料和简单追踪，未必足够轻

### 4. Fishbowl Manufacturing

Fishbowl 的优势在 inventory control、production planning、order tracking、BOM、reorder quantity。它对“材料、生产、库存”这件事非常成熟。

适合的场景：

- 原材料 / 半成品 / 成品库存管理
- 生产流程控制
- 自动补货和 work order 管理

不足：

- 更强的是内部制造和库存，不是 customer-facing
- 对“客户自己下载 app 追工期”这类 portal 不是主线

### 5. BSimple

BSimple 的亮点是 customer ordering portal、real-time inventory tracking、automatic purchase order generation。它很适合“客户下单 + 库存可见 + 自动补货”的业务。

适合的场景：

- 客户 portal
- 订单状态和库存透明化
- 自动采购补货

不足：

- 更像订单和库存系统，不是现场生产执行系统
- 对 workshop supervisor 的实时进度回报不够聚焦

## ForgeFlow 的空档

从这些产品看，ForgeFlow 可能站在一个交叉点上：

- JAQ 覆盖 job 和 workshop，但客户端弱
- Nexvia 连接 office 和 production，但偏项目型和重管理
- Wiise 很全，但重、复杂、实施门槛高
- Fishbowl 强库存与生产，但不强调客户追踪
- BSimple 强 portal 和库存，但不够 workshop-native

### 机会点

ForgeFlow 如果要成立，比较像是在做一个更轻、更实时、更 workshop-native 的工具，重点不是“取代 ERP”，而是：

1. 现场缺料一键上报
2. project status 实时同步
3. 材料库存看板
4. 客户只看自己项目的工期进度
5. 让 office、workshop、customer 共享同一套轻量状态

## 初步判断

澳洲不是没有解决方案，而是现有方案大多已经很成熟、也很重。你的机会更可能出现在：

- 细分到 workshop / fabrication 场景
- 更简单的 mobile-first workflow
- 更实时的补料和进度回报
- 更轻的 customer visibility

## 参考来源

- [JAQ](https://www.jaq.com.au/)
- [Nexvia Production Portal](https://nexvia.com.au/product/production/)
- [Wiise Warehouse OnTime](https://www.wiise.com/wiise-warehouse-ontime)
- [Wiise Jobs & Projects](https://www.wiise.com/job-project-costing)
- [Fishbowl Inventory Australia](https://www.fishbowlinventory.com.au/)
- [Fishbowl Manufacturing](https://www.fishbowlinventory.com.au/products/fishbowl-manufacturing/)
- [BSimple Inventory Management System](https://bsimple.com.au/inventory-management-system-cloud-based/)
- [BSimple Order Management System](https://bsimple.com.au/order-online/)
