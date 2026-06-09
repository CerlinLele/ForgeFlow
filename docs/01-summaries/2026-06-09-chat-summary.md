# ForgeFlow 项目归纳

## 项目背景

这段聊天讨论的是一个面向 manufacturing / workshop 制造行业的管理工具想法。核心场景来自澳洲中小型制造业公司，尤其是金属加工、焊接、钢材加工、车间生产这类业务。

当前问题不是单纯的任务管理，而是项目进度、材料库存、补料请求、office 管理和客户沟通之间缺少实时闭环。

## 一句话概括

ForgeFlow 是一个为制造业 workshop 设计的实时项目进度、材料库存、补料提醒和客户工期追踪系统。

## 当前工作流

1. 每个 project 开工前都需要对应材料，例如方管、圆管、角钢、槽钢、round bar 等。
2. Workshop supervisor 每天人工回报项目进度，例如 20%、80%。
3. 如果现场发现缺料，需要通知 office 或 manager。
4. Manager 可能几个小时后才处理，甚至忘记叫料。
5. 客户如果想知道工期，只能打电话问 project manager。
6. 信息在 workshop、office、供应商和客户之间流动慢，容易断层。

## 核心痛点

### 1. 缺料不能即时上报

现场发现材料不够时，office / manager 不一定能马上知道，导致项目停工。

### 2. 补料流程容易断掉

Manager 可能忘记联系供应商叫料，或者补料请求没有被持续追踪。

### 3. 项目进度不透明

目前依赖每日人工汇报，进度只是大概百分比，不够实时，也不够细。

### 4. Workshop 和 office 信息不同步

内场 workshop supervisor 和 office manager 之间缺少统一系统，很多事情靠口头、电话、消息或人工记忆。

### 5. 客户频繁追问工期

客户不知道项目做到哪一步，只能反复打电话给 project manager，增加沟通成本。

### 6. Middle management 效率低

聊天中提到这个工具有机会减少低效的中间沟通，让现场信息直接同步给管理层和客户。

## 产品机会

ForgeFlow 可以把以下几个信息流串起来：

- Project progress：项目做到哪一步。
- Material stock：材料库存还剩多少。
- Reorder request：哪些材料需要补。
- Workshop-office sync：现场和办公室实时同步。
- Customer visibility：客户可以看到自己的项目进度。

## MVP 功能方向

第一版可以先聚焦最小可行功能：

1. 创建 project。
2. 给 project 更新进度。
3. 标记 project 是否缺料。
4. 提交缺料请求。
5. 查看材料库存。
6. Manager 收到补料提醒。
7. 客户查看项目状态。

## 后续可扩展功能

- 材料库存后台，例如角钢 50x50、圆管 32NB、槽钢等剩余数量。
- 库存低于阈值自动提醒。
- 供应商管理。
- 采购单和到货状态。
- 项目延迟原因记录。
- 客户端项目追踪页面。
- 车间看板。
- Manager dashboard。

## 需要继续向行业用户确认的问题

1. 一个 project 从接单到完成，中间有哪些步骤？
2. 哪些步骤最容易因为缺料卡住？
3. 缺料现在是谁发现、谁记录、谁通知、谁采购？
4. 现在使用 Excel、纸、WhatsApp、Email，还是已有 ERP？
5. Manager 每天最想看到哪些信息？
6. 客户最常问 project manager 什么？
7. 材料库存现在有没有系统记录？
8. 一次缺料平均会造成多久延迟？

## 初步定位

ForgeFlow 不是普通 task management app，而是一个制造业垂直 SaaS。它的核心价值是让车间现场、office、供应商和客户围绕同一个 project 和 material status 实时同步。

## 初步英文 slogan

Real-time workflow and material tracking for manufacturing workshops.
