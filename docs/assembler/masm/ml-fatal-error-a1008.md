---
title: "ML Fatal Error A1008 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: ["A1008"]
dev_langs: ["C++"]
helpviewer_keywords: ["A1008"]
ms.assetid: fe592f9d-c37b-4cd8-a51d-e3c15ddcab83
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
ms.workload: ["cplusplus"]
---
# ML Fatal Error A1008
**unmatched macro nesting**  
  
 Either a macro was not terminated before the end of the file or the terminating directive [ENDM](../../assembler/masm/endm.md) was found outside of a macro block.  
  
 One cause of this error is omission of the dot before [.REPEAT](../../assembler/masm/dot-repeat.md) or [.WHILE](../../assembler/masm/dot-while.md).  
  
## See Also  
 [ML Error Messages](../../assembler/masm/ml-error-messages.md)