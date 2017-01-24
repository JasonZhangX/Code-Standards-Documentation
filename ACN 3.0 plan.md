#ACN Front-end Development Plan
-----
Author: Jason Zhang
Last update:　20161025

##Plan List

- #### [Azure UI Component Demo Page and API Document](#plan-1)
- #### [AzureX Javascript Library API Document](#plan-2)
- #### [ACN Front-end Performance Optimization](#plan-3)
- #### [Azure UI Front-end Engineering](#plan-4)
- #### [Template Code Refector](#plan-5)
- #### [Front-end Code Specification Document](#plan-6)
- #### [Static Resource Specification Document(Static Resource Management System)](#plan-7)
- #### [Caculator Refector(Base on MVC Framework)](#plan-8)


| Project Name | Priority | Spend Time |
|--------|--------|--------|
| Azure UI Component Demo Page and API Document |    1    |  3 weeks |
| AzureX Javascript Library API Document |    1    |  1 week |
| ACN Front-end Performance Optimization |    1    |  2 weeks |
| Azure UI Front-end Engineering |    1    |  2 weeks |
| Template Code Refector |    1    |  1 week |
| Front-end Code Specification Document |    2    |  1 week |
| Static Resource Specification Document(Static Resource Management System) |    1    |  1 week (3 weeks) |
| Caculator Refector(Base on MVC Framework) |   3    |  4 weeks |

##<a name="plan-1"></a>Azure UI Component Demo Page and API Document
**Description**: 所有的Azure组件分类整理展示页面以及使用代码示例，供content team已经其他dev快速构建页面和学习如何使用组件。

Tasks

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| Arrange Component Category | 1 | 1 day |
| Component Demo Page Framework | 1 | 5 day |
| Fill Component Data | 2 | TBD |

##<a name="plan-2"></a>AzureX Javascript Library API Document
**Description**: 基础Javascript功能封装，避免重复开发。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| Common Function Packaging | 1 | 5 day |
| Comprehensive Test | 1 | 2 day |

##<a name="plan-3"></a>ACN Front-end Performance Optimization
**Description**: 模块合并，SVG合并，PNG合并，提高页面性能。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| Merge module to AzureUI | 1 | 3 day |
| Merge SVG | 1 | 3 day |

##<a name="plan-4"></a>Azure UI Front-end Engineering
**Description**: 自动建立静态服务器，在C#项目外独立开发前端以提高开发效率，建立watcher监控代码更新自动刷新页面，自动代码检查，自动化测试，开发模式调用未压缩文件，正式部署后调用压缩文件。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| 工作流程整理优化 | 1 | 2 day |
| 重新整理自动化逻辑 | 1 | 2 day |
| 添加Nodejs前端模板支持 | 1 | 2 day |
| 添加自动化测试 | 1 | 2 day |
| 添加自动化代码检查 | 1 | 2 day |

##<a name="plan-5"></a>Template Code Refector
**Description**: 调整template结构，把Javascript和CSS入口和ID的关系转移到外部JSON文件配置以精简template数量。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| 把template id 和 css/js 依赖关系整理到json文件中 | 1 | 2 day |
| C#外部调用JSON文件渲染到template中 | 1 | 4 day |

##<a name="plan-6"></a> Front-end Code Specification Document
**Description**: 前端代码规范文档，保证team内部代码风格一致性以及避免低级错误的发生。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| HTML Code Specification Document | 1 | 2 day |
| LESS Code Specification Document | 1 | 2 day |
| Javascript Code Specification Document | 2 | 2 day |

##<a name="plan-7"></a>Static Resource Specification Document(Static Resource Management System)
**Description**: 静态资源规范文档（静态资源管理系统）。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| 制定静态资源规范 | 1 | 2 day |

##<a name="plan-8"></a>Caculator Refector(Base on MVC Framework)
**Description**: 使用MVC框架重构价格计算器前端，优化性能以及交互体验。

| Task Name | Priority | Spend Time |
|--------|--------|--------|
| 分析需求调研MVC框架 | 3 | 2 day |