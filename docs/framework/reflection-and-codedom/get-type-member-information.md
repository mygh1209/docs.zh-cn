---
title: 如何：使用反射获取类型和成员信息
ms.date: 09/03/2019
helpviewer_keywords:
- reflection, obtaining member information
- types [.NET Framework], obtaining member information from
ms.assetid: 348ae651-ccda-4f13-8eda-19e8337e9438
author: rpetrusha
ms.author: ronpet
dev_langs:
- cpp
- csharp
- vb
ms.openlocfilehash: da71845ea276267220636cfd661465ea02b2b50d
ms.sourcegitcommit: 7b1ce327e8c84f115f007be4728d29a89efe11ef
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/13/2019
ms.locfileid: "70972857"
---
# <a name="how-to-get-type-and-member-information-by-using-reflection"></a><span data-ttu-id="1168b-102">如何：使用反射获取类型和成员信息</span><span class="sxs-lookup"><span data-stu-id="1168b-102">How to: Get type and member information by using reflection</span></span>
<span data-ttu-id="1168b-103"><xref:System.Reflection> 命名空间包含许多获取关于类型及其成员的信息的方法。</span><span class="sxs-lookup"><span data-stu-id="1168b-103">The <xref:System.Reflection> namespace contains many methods for obtaining information about types and their members.</span></span> <span data-ttu-id="1168b-104">本文介绍其中一种方法：<xref:System.Type.GetMembers%2A?displayProperty=nameWithType>。</span><span class="sxs-lookup"><span data-stu-id="1168b-104">This article demonstrates one of these methods, <xref:System.Type.GetMembers%2A?displayProperty=nameWithType>.</span></span> <span data-ttu-id="1168b-105">有关其他信息，请参阅[反射概述](reflection.md)。</span><span class="sxs-lookup"><span data-stu-id="1168b-105">For additional information, see [Reflection overview](reflection.md).</span></span>
  
## <a name="example"></a><span data-ttu-id="1168b-106">示例</span><span class="sxs-lookup"><span data-stu-id="1168b-106">Example</span></span>

<span data-ttu-id="1168b-107">下例演示通过使用反射获取类型和成员信息：</span><span class="sxs-lookup"><span data-stu-id="1168b-107">The following example obtains type and member information by using reflection:</span></span>

[!code-cpp[Get type members](../../../samples/snippets/standard/reflection/memberinfo/gettypemembers.cpp)]
[!code-csharp[Get type members](../../../samples/snippets/standard/reflection/memberinfo/gettypemembers.cs)]
[!code-vb[Get type members](../../../samples/snippets/standard/reflection/memberinfo/gettypemembers.vb)]

## <a name="see-also"></a><span data-ttu-id="1168b-108">请参阅</span><span class="sxs-lookup"><span data-stu-id="1168b-108">See also</span></span>

- [<span data-ttu-id="1168b-109">使用应用程序域进行编程</span><span class="sxs-lookup"><span data-stu-id="1168b-109">Program with application domains</span></span>](../app-domains/application-domains.md#programming-with-application-domains)
- [<span data-ttu-id="1168b-110">反射</span><span class="sxs-lookup"><span data-stu-id="1168b-110">Reflection</span></span>](reflection.md)
- [<span data-ttu-id="1168b-111">使用应用程序域</span><span class="sxs-lookup"><span data-stu-id="1168b-111">Use application domains</span></span>](../app-domains/use.md)