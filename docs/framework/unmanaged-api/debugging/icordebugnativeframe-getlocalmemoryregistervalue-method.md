---
title: "ICorDebugNativeFrame::GetLocalMemoryRegisterValue 方法"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology:
- dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name:
- ICorDebugNativeFrame.GetLocalMemoryRegisterValue
api_location:
- mscordbi.dll
api_type:
- COM
f1_keywords:
- ICorDebugNativeFrame::GetLocalMemoryRegisterValue
helpviewer_keywords:
- ICorDebugNativeFrame::GetLocalMemoryRegisterValue method [.NET Framework debugging]
- GetLocalMemoryRegisterValue method
ms.assetid: 33a19f6e-1029-4d53-af64-19591c6e58ee
topic_type:
- apiref
caps.latest.revision: 
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.workload:
- dotnet
ms.openlocfilehash: 19b3a184272af06e465257d317ab32f5a9c3686a
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="icordebugnativeframegetlocalmemoryregistervalue-method"></a>ICorDebugNativeFrame::GetLocalMemoryRegisterValue 方法
获取的参数或局部变量，其中的低位字和高位字分别存储在指定的寄存器和内存位置，此本机帧的值。  
  
## <a name="syntax"></a>语法  
  
```  
HRESULT GetLocalMemoryRegisterValue (  
    [in] CORDB_ADDRESS      highWordAddress,  
    [in] CorDebugRegister   lowWordRegister,  
    [in] ULONG              cbSigBlob,  
    [in] PCCOR_SIGNATURE    pvSigBlob,  
    [out] ICorDebugValue    **ppValue  
);  
```  
  
#### <a name="parameters"></a>参数  
 `highWordAddress`  
 [in]A`CORDB_ADDRESS`值，该值指定内存位置包含值的高位字。  
  
 `lowWordRegister`  
 [in]指定包含值的低位字的寄存器"CorDebugRegister"枚举的值。  
  
 `cbSigBlob`  
 [in]一个整数，指定的二进制元数据签名，这由引用的大小`pvSigBlob`参数。  
  
 `pvSigBlob`  
 [in]A`PCCOR_SIGNATURE`值，该值指向的值类型的二进制元数据签名。  
  
 `ppValue`  
 [out]指向表示检索到的值存储在指定的注册和内存位置的"ICorDebugValue"对象的地址的指针。  
  
## <a name="requirements"></a>惠?  
 **平台：**请参阅[系统要求](../../../../docs/framework/get-started/system-requirements.md)。  
  
 **标头：** CorDebug.idl、 CorDebug.h  
  
 **库：** CorGuids.lib  
  
 **.NET framework 版本：**[!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## <a name="see-also"></a>请参阅  
 
