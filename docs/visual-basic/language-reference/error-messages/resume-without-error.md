---
title: 无错误继续执行
ms.date: 07/20/2015
f1_keywords:
- vbrID20
ms.assetid: f9631804-fd36-4443-b36c-30db827e6176
ms.openlocfilehash: b6b565c88acadca048ade22ab00ac68539725f78
ms.sourcegitcommit: f8c270376ed905f6a8896ce0fe25b4f4b38ff498
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/04/2020
ms.locfileid: "84400365"
---
# <a name="resume-without-error"></a>无错误继续执行
`Resume`语句出现在错误处理代码之外，或代码跳转到错误处理程序，即使没有出错。  
  
## <a name="to-correct-this-error"></a>更正此错误  
  
1. 将 `Resume` 语句移动到错误处理程序中，或将其删除。  
  
2. 跳转到标签不能跨过程出现，因此请在过程中搜索标识错误处理程序的标签。 如果找到指定为不是语句的语句目标的重复标签 `GoTo` `On Error GoTo` ，则更改行标签以同意其预期目标。  
  
## <a name="see-also"></a>另请参阅

- [Resume 语句](../statements/resume-statement.md)
- [On Error 语句](../statements/on-error-statement.md)
