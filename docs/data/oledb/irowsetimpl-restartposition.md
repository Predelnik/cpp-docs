---
title: "IRowsetImpl::RestartPosition | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["ATL.IRowsetImpl.RestartPosition", "IRowsetImpl::RestartPosition", "RestartPosition", "ATL::IRowsetImpl::RestartPosition", "IRowsetImpl.RestartPosition"]
dev_langs: ["C++"]
helpviewer_keywords: ["RestartPosition method"]
ms.assetid: 14de66ef-8d2c-4404-adb6-3f6c74ac6cf1
caps.latest.revision: 8
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "data-storage"]
---
# IRowsetImpl::RestartPosition
Repositions the next fetch position to its initial position; that is, its position when the rowset was first created.  
  
## Syntax  
  
```cpp
      STDMETHOD(RestartPosition )(HCHAPTER /* hReserved */);  
```  
  
#### Parameters  
 See [IRowset::RestartPosition](https://msdn.microsoft.com/en-us/library/ms712877.aspx) in the *OLE DB Programmer's Reference*.  
  
## Remarks  
 The rowset position is undefined until **GetNextRow** is called. You can move backwards in a rowet by calling `RestartPosition` and then fetching or scrolling backwards.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetImpl Class](../../data/oledb/irowsetimpl-class.md)