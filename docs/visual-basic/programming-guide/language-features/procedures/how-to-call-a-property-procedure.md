---
title: "如何：调用 Property 过程 (Visual Basic)"
ms.custom: 
ms.date: 07/20/2015
ms.prod: .net
ms.reviewer: 
ms.suite: 
ms.technology: devlang-visual-basic
ms.topic: article
helpviewer_keywords:
- Visual Basic code, procedures
- Visual Basic code, properties
- procedures [Visual Basic], calling
- properties [Visual Basic], property procedures
- procedure calls [Visual Basic], property procedures
ms.assetid: 96bc4d74-d9c3-4b7a-954d-58ac8553cd94
caps.latest.revision: "16"
author: dotnet-bot
ms.author: dotnetcontent
ms.openlocfilehash: cf9080e3c2b23302257499f13e734231f3614495
ms.sourcegitcommit: 4f3fef493080a43e70e951223894768d36ce430a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/21/2017
---
# <a name="how-to-call-a-property-procedure-visual-basic"></a>如何：调用 Property 过程 (Visual Basic)
通过将值存储在属性中或检索其值调用 property 过程。 访问的属性相同的方式访问的变量。  
  
 该属性的`Set`过程存储一个值，并将其`Get`过程检索的值。 但是，你不显式调用这些过程的名称。 就像将存储或检索变量的值时，才使用赋值语句或表达式中的属性。 [!INCLUDE[vbprvb](~/includes/vbprvb-md.md)]调用属性的过程。  
  
### <a name="to-call-a-propertys-get-procedure"></a>调用属性的 Get 过程  
  
1.  你将使用的变量的名称相同的方式的表达式中使用的属性名称。 你可以使用属性任意位置，你可以使用变量或常量。  
  
     - 或 -  
  
     使用以下等的属性名称 (`=`) 在赋值语句登录。  
  
     下面的示例读取值<xref:Microsoft.VisualBasic.DateAndTime.Now%2A>属性，隐式调用其`Get`过程。  
  
     [!code-vb[VbVbalrDateProperties#4](./codesnippet/VisualBasic/how-to-call-a-property-procedure_1.vb)]  
  
2.  如果该属性接受参数，请按照用括号将自变量列表括起来的属性名称。 如果不有任何自变量，你可以选择省略括号。  
  
3.  将自变量放在括号里，用逗号分隔参数列表中。 请确保你提供属性定义的相应参数的相同顺序的自变量。  
  
 属性的值参与像变量表达式或常数那样，或存储在变量或赋值语句左侧的属性。  
  
### <a name="to-call-a-propertys-set-procedure"></a>若要调用属性的设置过程  
  
1.  在赋值语句的左侧使用的属性名称。  
  
     下面的示例设置的值<xref:Microsoft.VisualBasic.DateAndTime.TimeOfDay%2A>属性，隐式调用`Set`过程。  
  
     [!code-vb[VbVbcnProcedures#11](./codesnippet/VisualBasic/how-to-call-a-property-procedure_2.vb)]  
  
2.  如果该属性接受参数，请按照用括号将自变量列表括起来的属性名称。 如果不有任何自变量，你可以选择省略括号。  
  
3.  将自变量放在括号里，用逗号分隔参数列表中。 请确保你提供属性定义的相应参数的相同顺序的自变量。  
  
 赋值语句右侧生成的值存储在属性。  
  
## <a name="see-also"></a>另请参阅  
 [属性过程](./property-procedures.md)  
 [过程参数和自变量](./procedure-parameters-and-arguments.md)  
 [Property 语句](../../../../visual-basic/language-reference/statements/property-statement.md)  
 [在 Visual Basic 中属性和变量之间的差异](./differences-between-properties-and-variables.md)  
 [如何：创建属性](./how-to-create-a-property.md)  
 [如何：声明具有混合访问级别的属性](./how-to-declare-a-property-with-mixed-access-levels.md)  
 [如何： 声明和 Visual Basic 中调用默认属性](./how-to-declare-and-call-a-default-property.md)  
 [如何：在属性中放置值](./how-to-put-a-value-in-a-property.md)  
 [如何：从属性获取值](./how-to-get-a-value-from-a-property.md)  
 [Get 语句](../../../../visual-basic/language-reference/statements/get-statement.md)  
 [Set 语句](../../../../visual-basic/language-reference/statements/set-statement.md)
