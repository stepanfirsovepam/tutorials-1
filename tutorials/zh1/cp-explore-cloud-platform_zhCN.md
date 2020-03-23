---
title: 从更高层次查看 SAP Cloud Platform
description: 从开发人员的角度探索 SAP Cloud Platform，并了解账户、环境等的概念。
auto_validation: true
author_name: Marius Obert
author_profile: https://github.com/iobert
primary_tag: products>sap-cloud-platform
tags: [ tutorial>beginner, topic>cloud, products>sap-cloud-platform ]
time: 10
---


无需做任何准备。如果要开始了解 SAP Cloud Platform，这只是基础内容。

### 您将了解  
  - 什么是 SAP Cloud Platform？
  - SaaS、PaaS 和 IaaS 是什么及其工作原理？
  - 有哪些服务，我在哪里可以找到它们？
  - SAP Cloud Platform 有哪些不同的类型？
  - 组织和账户如何组合到一起？


[ACCORDION-BEGIN [Step](SAP Cloud Platform 简介)]

**欢迎使用 SAP Cloud Platform**

SAP Cloud Platform 是一组开放式软件、平台和基础架构即服务系统，提供内存功能、核心平台服务和独特的微服务，用于构建和扩展智能、移动和启用浏览器的应用程序。  SAP Cloud Platform 是多语言平台，支持大多数主要语言（[现在包括 ABAP](https://blogs.sap.com/2018/09/04/sap-cloud-platform-abap-environment/)），同时支持组织内部和广大公众的开发、测试和生产系统。  

SAP Cloud Platform 提供了大量 SAP 软件包或服务，可提供企业预置 SAP 应用程序的所有功能，但始终以云为中心。  它还为开发人员提供了一种定制这些服务或构建全新应用程序的方法，以向您的组织提供个性化的自定义应用程序。

SAP Cloud Platform 也在不断发展。  SAP 不断更新我们提供的服务、运行自定义代码的平台以及支持所有内容的基础架构。  这使开发人员可以专注于自定义代码，而不必担心硬件维护或软件升级。

让我们首先概述一下 SAP Cloud Platform 提供的不同类型的“即服务”。


[DONE]
[ACCORDION-END]






[ACCORDION-BEGIN [Step](“即服务”有什么含义？)]

在云计算中广泛使用的术语是“*某物*即服务”。  在这种情况下，服务表示云中为组织提供的一切内容。  因此，该术语的重要部分是第一个词 - *某物*。

组织可以通过多种方式购买和使用云资源。  最常见的四种方式：

- 企业预置（由于云中没有任何内容，因此都不是“服务”）
- 基础架构即服务 (IaaS)
- 平台即服务 (PaaS)
- 软件即服务 (SaaS)


三种不同的服务级别：

| 缩略词 | 名称 | 描述 |
| ------- | ------------ | ----------- |
| IaaS | 基础架构即服务 | 云提供硬件，客户提供操作系统以及其他所有内容。|
| PaaS | 平台即服务| 云提供硬件和操作系统。  客户选择应用程序并提供软件。|
| SaaS | 软件即服务| 云提供硬件、操作系统和软件。  客户可以直接使用此软件，无需更改或定制即可满足其业务需求。|



[DONE]
[ACCORDION-END]






[ACCORDION-BEGIN [Step](SAP Cloud Platform 服务类型)]

SAP Cloud Platform 提供了平台即服务 (PaaS) 和软件即服务 (SaaS)。  

为什么 SAP 同时提供这两种服务？  PaaS 和 SaaS 的组合提供了我们传统上销售的所有工具、特定于云的新工具，并能够根据每个组织的需求定制我们的所有产品。  

SAP Cloud 中提供了许多 SaaS 解决方案。  这些解决方案包括核心包 S/4HANA 以及人力资源工作流和物联网等新产品。  列表中还有更多内容，因此 [请查看更完整的列表以了解详细信息](https://cloudplatform.sap.com/support/service-description.html)。

> **注意**：此处描述了两种不同类型的服务。  上面列出的软件是独立软件包，无需定制即可使用。  这些都是软件即服务，但是我们将这些应用程序称为**解决方案**。  
>
> SAP Cloud Platform 还提供称为“平台服务”的服务，该服务为自定义代码提供附加功能。这些“平台服务”不是独立运行的。  SAP 将这些服务称为**服务**，尤其是在 Cloud Foundry 中。  因此，在之后的教程中看到“服务”这个名称时，通常表示“平台服务”。

SAP 还提供平台即服务 (PaaS)。  开发人员几乎可以使用任何语言编写代码，并使用我们的服务在同一云中运行该软件。  组织可以使用 PaaS 来运行独立软件，或定制 SAP 服务以满足特定需求。

---

最后，SAP 还提供云中的 IaaS。  我们之前没有提到它，因为它不经常使用。  但是，如果组织需要灵活性来运行非常特定的操作系统和软件配置，则我们的数据中心可以作为 SAP 云的一部分来提供支持。


[DONE]
[ACCORDION-END]





[ACCORDION-BEGIN [Step](SAP Cloud Platform 数据中心)]

SAP Cloud Platform 可用于两种不同类型的数据中心。  首先，SAP 在全球范围内运行自己的数据中心，并针对 SAP 软件进行了优化。  其次，SAP 还与其他云基础架构提供商合作。  目前，我们的合作伙伴有 Amazon Web Services (AWS)、Microsoft Azure 和 Google Cloud Platform (GCP)。

![数据中心位置和类型](4.png)

这是全球所有 SAP 数据中心的图形表示。  [此页面还包含中心类型以及每个数据中心提供的服务的完整列表](https://help.sap.com/doc/aa1ccd10da6c4337aa737df2ead1855b/Cloud/en-US/3b642f68227b4b1398d2ce1a5351389a.html)。

服务和数据中心的列表会不断更新，因此请使用此链接查找最新信息。






[DONE]
[ACCORDION-END]






[ACCORDION-BEGIN [Step](Neo、Cloud Foundry 和 ABAP)]

SAP 云中存在三种不同的 PaaS 环境。

第一个环境称为 "Neo"。  这是原始 SAP 运行时环境。  利用 Neo 环境，您可以开发 HTML5、Java 和 SAP HANA 扩展应用程序服务 (SAP HANA XS) 应用程序。您还可以使用面向 HTML5 的 UI 开发工具包 (SAPUI5) 开发面向现代基于 Web 的业务应用程序的丰富用户界面。  Neo 在 SAP 维护和支持的服务器上的 SAP Cloud Platform 中运行。

第二个环境是 Cloud Foundry。  该环境于 2017 年添加。  [Cloud Foundry 是开源项目和标准](https://www.cloudfoundry.org/)，由 Cloud Foundry 基金会运行（在此之前是 Linux 基金会）。  SAP 已使用我们不断扩展的第三方数据中心（例如 AWS、Azure 和 Google Cloud）网络中的服务器在 SAP Cloud Platform 上实施 Cloud Foundry。

最新的环境是 [ABAP 环境](https://cloudplatform.sap.com/enterprise-paas/abap.html)，允许您为基于 ABAP 的产品（例如 SAP S/4HANA Cloud）创建扩展，并开发新的云应用程序。您可以将现有基于 ABAP 的自定义代码或扩展传输到云。


哪种环境适合您？  这个问题不错。  每种环境都有其优势，某些服务仅可用于其中一种环境。  在做出决策之前首先了解所有的环境，然后使用我们的 [在线地图为您提供指导](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/73beb06e127f4e47b849aa95344aabe1.html)。



[DONE]
[ACCORDION-END]





[ACCORDION-BEGIN [Step](SAP Cloud Foundry 主控室)]

从 [SAP Cloud Platform 主控室](https://account.hanatrial.ondemand.com/register) 开始访问 SAP Cloud Foundry。

![主控室登录页面的图像](cockpit-main.png)

开发人员可以访问 SAP Cloud Platform 主控室以登录并访问云中的 PaaS 和 SaaS 系统。  

> 将该链接添加为书签以快速访问主控室。  
>&nbsp;

> 主控室中的每个页面都是一个单独的 URL，因此也可以为这些页面添加书签，以便更快速地访问常用页面。





[DONE]
[ACCORDION-END]






[ACCORDION-BEGIN [Step](SAP Cloud Platform 上的试用账户)]

SAP 提供 [SAP Cloud Platform 免费试用版](https://account.hanatrial.ondemand.com/register)。  Neo 和 Cloud Foundry 环境均可试用。  

Neo 环境终身免费试用，并且永不过期。  

![Neo 环境开始页面](neo-environment.png)

Cloud Foundry 试用版在 90 天后过期，但可以根据需要多次延期。

![Cloud Foundry 空间页面](cf-spaces-page.png)

之后的教程将介绍如何为 Neo 和 Cloud Foundry 创建账户。



[DONE]
[ACCORDION-END]



[ACCORDION-BEGIN [Step](账户和子账户)]

SAP Cloud Platform 使用两个级别的账户：全局账户和子账户。  

全局账户是您的组织或团队的主要账户。  它是所有资源的中央池。  不能直接访问全局账户，它只充当所有子账户的“伞”或容器。

![全局账户主页](global-accounts-home.png)

子账户由全局账户创建，可用于细分资源。  每个子账户都有一个不同的名称。

![子账户主页](sub-accounts-home.png)

每个子账户都会通过“权利”获得一份资源。  资源可以分配给单个子账户，也可以分配给多个子账户。  然后，当任意单个子账户需要更多资源时，可以在此处进行分配。

![子账户的权利](entitlements.png)

> **注意**
>
> 试用账户具有一个全局账户和一个子账户。  大部分详细信息对于试用账户并不重要，但如果您要进行更复杂的设置，那么最好了解所有工作原理。





[DONE]
[ACCORDION-END]





结束！  这就是 SAP Cloud Platform 的更高层次概览。  请按照后续教程获取一个试用账户，配置该账户，然后开始使用上述服务并针对云编写新代码。  希望您能乐在其中！


---
