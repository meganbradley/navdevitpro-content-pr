---
title: "Create Method"
ms.author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 27/06/2017
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: "dynamics-nav-2017"
ms.assetid: 620f0e32-eadc-43e9-8f6e-8fc0b12c3aaf
caps.latest.revision: 1
manager: edupont
author: SusanneWindfeldPedersen
---

# Create Method
Creates an XmlAttribute.  
```  
XmlAttribute := XmlAttribute.Create(Name, Value)  
```  
## Parameters
*Name*    
&emsp;Type: String  
The qualified name of the attribute. If the name is of the form {namespace}localName, it will be qualified with the given namespace.  
  
*Value*    
&emsp;Type: String  
The value of the attribute.  
  
## Return Value
*XmlAttribute*  
&emsp;Type: XmlAttribute  
  
## See Also
[Getting Started](../devenv-get-started.md)  
[Developing Extensions Using the New Development Environment](../devenv-dev-overview.md)  