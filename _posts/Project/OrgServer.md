---
layout: project

title: 组织管理系统
categories:
  - Project
tags:
  - organization
  - management
  - service
  - Strapi
  - CMS
  - JavaScript
  - RESTful API

description: 基于 Strapi 构建的适用于各种组织的数据服务器脚手架
logo: https://github.com/strapi.png
website:
repository: https://github.com/kaiyuanshe/OrgServer
---

本项目基于[开源社][1]、[freeCodeCamp 成都社区][2]等组织的**运营经验**打造

## 数据结构

### 模型

|   集合类型   |     用途     |           备注           |
| :----------: | :----------: | :----------------------: |
|   Category   |   内容分类   |  可关联于多种内容型数据  |
|   Comment    |   内容评论   |  可关联于多种内容型数据  |
|   Account    |     账目     |     赞助、差旅、采购     |
|   Property   |     物资     |       设备、纪念品       |
|     User     | 外部注册用户 |        非后台用户        |
| Organization |   外部组织   | 公司、开源社区、公益组织 |
|    Place     |     场地     |        室内、户外        |
|   Project    |     专案     |      开源、公益项目      |
|     Task     |     任务     |                          |
| Contribution |   任务贡献   |                          |
|   Program    |   活动环节   |    演讲、工作坊、展位    |
|   Activity   |     活动     |     各类小中大型活动     |
| PartnerShip  |   合作关系   |      活动合作、赞助      |
|  Evaluation  |     评价     |   贡献、活动环节的评分   |

### 组件

|  名称  |   分类   |     用途     |
| :----: | :------: | :----------: |
| Period |   Date   |     周期     |
| Goods  | Supplies | 设备、纪念品 |

[1]: https://kaiyuanshe.cn/
[2]: https://fcc-cd.dev/
