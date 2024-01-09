# 软件开发

在软件系统的幕后，开发与维护的规范则扮演着重要角色。通过遵循良好的开发实践，我们能够确保工程设计的可读性、可维护性和可扩展性。
活字格设计器“所见即所得”的特性，决定了软件开发的诸多环节，仍可以遵照[界面展示](/standard/principle/design)中的原则赋予新的理解。

## 一致性

团队或项目中请保持一致的开发风格、开发流程和第三方工具使用等方面的特性。详细内容请阅读[开发规范](/standard/dev/naming-style)。

::: info 📘关于开发风格的说明

在软件开发中，"风格"（Style）通常是一种编写、组织或设计代码、文档等元素的特定方式或规范。
这种方式旨在提高代码的可读性、可维护性、一致性和可理解性。风格不仅包括代码的外观和格式，还包括对于整个项目结构、设计原则、文档等的规范。
可以参考如下的风格维度：
- 代码风格：包含所有可视化的逻辑设计规范，以及编码开发中的代码外观与格式的规则集。
- 设计风格：关注软件的整体架构和设计理念，包括模块划分、组件交互、系统层次结构等。
- 文档风格：包括文档的结构、格式、命名规范等，适用于代码注释、技术文档、用户文档等。
- 项目组织风格：涉及到源代码、配置文件、文档等在项目中的布局和组织方式。

:::

## 效率

活字格的灵活性会带来较强的开放性，会存在同一需求场景可能存在多种实现方式。在确保终端用户拥有良好使用体验的前提下，
简化度最高的设计思路应当被优先考虑。

::: tip 🤔我应该如何评估？

良好的使用体验与简化度是一个宽泛的概念，在不同的场景下理应当具有不同的定义。 通常来说：
- 良好的使用体验需要考量系统性能、用户感受、加载成本等；
- 从奥卡姆剃刀原理出发，评估当前方案的简洁度。
	> 奥卡姆剃刀原理：如无必要，勿增实体。如果您的场景能用原生的方式进行实现，就不要引入第三方库；如果必须要引入第三方库来解决，就选择最简单的那个库。
  
:::

设计器中的设计过程也应当简单直白，尽量发挥出可视化的优势，方便项目中其他协同的开发者快速识别功能，降低理解门槛。

## 可控

设计器中的所有设计行为应当遵循“约定优于配置”的思路，方便开发者按照相同的认知进行应用的开发设计。

> 约定优于配置（convention over configuration），也作按约定开发，它强调通过制定一些默认约定来减少配置的需要，
已在许多现代软件框架和工具中得到了广泛应用。

在活字格中，标准化的可视化设计已经具备了一定的约定效果，例如实现某些效果，使用指定的命令执行。不同的开发者在开发相同或类似的需求场景时，
他们的实现方式总是类似的。在后续的维护以及交接工作过程中，极大的降低了风险。

当然，在实施过程中，您可以针对具体的业务逻辑，定制团队专属的**设计约定**，团队内的任何成员在熟悉约定后，
都可以以相同的认知和类似的实施手段参与到开发设计工作中。

::: tip 💡TIP

本文档其实正在扮演了“约定”的角色。在您了解本文档所介绍的标准化后，便可以专业的活字格开发者的身份参与到您的项目开发中。

:::