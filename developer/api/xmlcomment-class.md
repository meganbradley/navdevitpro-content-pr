---
title: "XmlComment Class"
ms.author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 30/06/2017
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

[!INCLUDE[newdev_dev_preview](../includes/newdev_dev_preview.md)]

# XmlComment Class
Represents the content of an XML comment.

The following methods are available on the XmlComment class.  
  
|Method name|Description|  
|-----------|-----------|  
|[XmlComment.Create(String)](xmlcomment-create-method.md)|Creates an XmlComment node.|  
|[XmlComment.Value(String)](xmlcomment-value-property.md)|Gets or sets the string value of this comment.|  
|[XmlComment.AsXmlNode()](xmlcomment-asxmlnode-method.md)|Converts the node to an XmlNode.|  
|[XmlComment.GetParent(XmlElement)](xmlcomment-getparent-method.md)|Gets the parent XmlElement of this node.|  
|[XmlComment.GetDocument(XmlDocument)](xmlcomment-getdocument-method.md)|Gets the XmlDocument for this node.|  
|[XmlComment.AddAfterSelf(Joker)](xmlcomment-addafterself-method.md)|Adds the specified content immediately after this node.|  
|[XmlComment.AddBeforeSelf(Joker)](xmlcomment-addbeforeself-method.md)|Adds the specified content immediately before this node.|  
|[XmlComment.ReplaceWith(Joker)](xmlcomment-replacewith-method.md)|Replaces this node with the specified content.|  
|[XmlComment.Remove()](xmlcomment-remove-method.md)|Removes this node from its parent element.|  
|[XmlComment.WriteTo(OutStream)](xmlcomment-writeto-outstream-method.md)|Serializes and saves the current node to the given variable.|  
|[XmlComment.WriteTo(Text)](xmlcomment-writeto-text-method.md)|Serializes and saves the current node to the given variable.|  
|[XmlComment.SelectSingleNode(String, XmlNode)](xmlcomment-selectsinglenode-xpath-node-method.md)|Selects the first XmlNode that matches the XPath expression.|  
|[XmlComment.SelectSingleNode(String, XmlNamespaceManager, XmlNode)](xmlcomment-selectsinglenode-xpath-namespacemanager-node-method.md)|Selects the first XmlNode that matches the XPath expression.|  
|[XmlComment.SelectNodes(String, XmlNodeList)](xmlcomment-selectnodes-xpath-nodelist-method.md)|Selects a list of nodes matching the XPath expression.|  
|[XmlComment.SelectNodes(String, XmlNamespaceManager, XmlNodeList)](xmlcomment-selectnodes-xpath-namespacemanager-nodelist-method.md)|Selects a list of nodes matching the XPath expression.|  
## See Also
[Getting Started](../devenv-get-started.md)  
[Developing Extensions](../devenv-dev-overview.md)  