---
title: TcpTransportBindingElement
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: article
ms.assetid: 33bbc1e5-44e4-4ee3-b7b5-801dc78956e4
caps.latest.revision: "8"
author: dotnet-bot
ms.author: dotnetcontent
manager: wpickett
ms.workload: dotnet
ms.openlocfilehash: 6e230cbccee211fbda219000fbbd2cda5275776b
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="tcptransportbindingelement"></a>TcpTransportBindingElement
TcpTransportBindingElement  
  
## <a name="syntax"></a>语法  
  
```  
class TcpTransportBindingElement : ConnectionOrientedTransportBindingElement  
{  
  TcpConnectionPoolSettings ConnectionPoolSettings;  
  sint32 ListenBacklog;  
  boolean PortSharingEnabled;  
  boolean TeredoEnabled;  
};  
```  
  
## <a name="methods"></a>方法  
 TcpTransportBindingElement 类不定义任何方法。  
  
## <a name="properties"></a>属性  
 TcpTransportBindingElement 类具有以下属性：  
  
### <a name="connectionpoolsettings"></a>ConnectionPoolSettings  
 数据类型：TcpConnectionPoolSettings  
  
 访问类型：只读  
  
 连接池设置。  
  
### <a name="listenbacklog"></a>ListenBacklog  
 数据类型：sint32  
  
 访问类型：只读  
  
 可挂起的最大排队连接请求数。  
  
### <a name="portsharingenabled"></a>PortSharingEnabled  
 数据类型：Boolean  
  
 访问类型：只读  
  
 一个布尔值，指定是否为此连接启用 TCP 端口共享。  
  
### <a name="teredoenabled"></a>TeredoEnabled  
 数据类型：Boolean  
  
 访问类型：只读  
  
 一个布尔值，指定是否启用 Teredo（一种用于对防火墙后的客户端进行寻址的技术）。  
  
## <a name="requirements"></a>惠?  
  
|MOF|已在 Servicemodel.mof 中声明。|  
|---------|-----------------------------------|  
|命名空间|已在 root\ServiceModel 中定义|  
  
## <a name="see-also"></a>请参阅  
 <xref:System.ServiceModel.Channels.TcpTransportBindingElement>
