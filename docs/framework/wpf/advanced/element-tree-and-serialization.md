---
title: "元素树和序列化"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology:
- dotnet-wpf
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- AutoGeneratedOrientationPage
helpviewer_keywords:
- element tree [WPF]
- serialization [WPF]
- tree [WPF]
ms.assetid: 8f57e879-180b-421f-b3d0-ac007ff2ce80
caps.latest.revision: 
author: dotnet-bot
ms.author: dotnetcontent
manager: wpickett
ms.workload:
- dotnet
ms.openlocfilehash: 13affab3e1e6a1a732231763219e9b419ea7ea51
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="element-tree-and-serialization"></a>元素树和序列化
WPF 编程元素彼此之间通常以某种形式的树关系存在。 例如，XAML 中创建的应用程序 UI 可概念化为一个对象树。 可进一步将元素树分为两个离散但有时会并行的树：逻辑树和可视化树。 WPF 中的序列化涉及保存这两个树和应用程序的状态并将状态写入文件（可能以 XAML 形式）。  
  
## <a name="in-this-section"></a>本节内容  
 [WPF 中的树](../../../../docs/framework/wpf/advanced/trees-in-wpf.md)  
 [XamlWriter.Save 的序列化限制](../../../../docs/framework/wpf/advanced/serialization-limitations-of-xamlwriter-save.md)  
 [不在对象树中的对象元素的初始化](../../../../docs/framework/wpf/advanced/initialization-for-object-elements-not-in-an-object-tree.md)  
 [帮助主题](../../../../docs/framework/wpf/advanced/element-tree-and-serialization-how-to-topics.md)  
  
## <a name="reference"></a>参考  
 <xref:System.Windows.Markup>  
  
 <xref:System.Windows.LogicalTreeHelper>  
  
 <xref:System.Windows.Media.VisualTreeHelper>  
  
## <a name="related-sections"></a>相关章节  
 [WPF 体系结构](../../../../docs/framework/wpf/advanced/wpf-architecture.md)  
  [WPF 中的 XAML](../../../../docs/framework/wpf/advanced/xaml-in-wpf.md)  
  [基元素](../../../../docs/framework/wpf/advanced/base-elements.md)  
  [属性](../../../../docs/framework/wpf/advanced/properties-wpf.md)  
  [事件](../../../../docs/framework/wpf/advanced/events-wpf.md)  
  [输入](../../../../docs/framework/wpf/advanced/input-wpf.md)  
  [资源](../../../../docs/framework/wpf/advanced/resources-wpf.md)  
  [样式设置和模板化](../../../../docs/framework/wpf/controls/styling-and-templating.md)  
  [线程模型](../../../../docs/framework/wpf/advanced/threading-model.md)
