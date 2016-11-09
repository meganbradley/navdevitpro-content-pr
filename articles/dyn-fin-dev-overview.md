---
title: "Developing for Dynamics 365 for Financials Overview"
description: "Overview of the new development experience."
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 11/02/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: "dynamics-nav-2017"
ms.author: solsen
ms.assetID: be636361-9de8-4efb-ad50-445e4b7b3255
---

# Developing for Dynamics 365 for Financials Overview
Developing for [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] is done by creating an extension to a [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] solution.  Extensions are a programming model where functionality is defined as an addition to existing objects and defines how they are different or modify the behaviour of the solution. 
You might already be familiar with the extension model working with... For more information, see [old way of doing things description]().

If you're new to building extensions for [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)], we recommend that you read this document to get an understanding of the basics and terms you will encounter while working. Next, follow the [Getting Started Developing for Dynamics 365 for Financials](dyn-fin-geting-started-dev-env.md) to setup your system and then jump straight into your first extension - Hello World [link to hello world]().

## Understanding Objects in Dynamics 365 for Financials
All functionality in [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] is coded in an object. Table objects define the table schema that holds data, Page objects represent the pages seen in the user interface and codeunits contain code for logical calculations and for the application behavior. These objects are stored as code, known as AL code, and are saved in files with the ```.al``` file extension.  
    
    **Note:** A single AL file may contain multiple objects.      

There are two other special objects which are specifially used for building extensions. Table Extension objects and Page Extension Objects are used for defining additive or overriding changes to Page or Table objects. For example, an extension for managing a business that sells organic food may define a Table Extension object for the Item table that contains an additional field ```Organic``` and ```Produced Locally```. The ```Organic``` and ```Produced Locally``` fields aren't usually present in the Item table, but through the Table Extension these data fields will now be available to store data in and to access from code.

For more information, see [Page Extension Objects]() and [Table Extension Objects]().

## Developing Extensions in Visual Studio Code
Using the AL extension for Visual Studio Code, you'll get the benefits of a modern development environment along with seamless publishing and execution integration with your [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] tenant. For more information on getting up and running, see [Getting Started Developing for Dynamics 365 for Financials](../dynamics-nav/dyn-fin-geting-started-dev-env.md).

Visual Studio Code and the AL Extension lets you do all the following tasks, easily:

- New files for your solution
- Assistance with creating the appropriate configuration and setting files 
- Code snippets that provide templates for coding application objects
- Compiler validation while coding
- F5 to publish your changes and see your code running

For more information, see []().

## Syntax
The syntax of the AL language is designed to assist in building business applications. The AL language is an evolution from the original programming languge used in Dynamics NAV and resembles it very closely. The changes from the Dynamics NAV language and AL can be found in links in this section.

- Table Object Syntax
- Table Extension Object Syntax
- Page Object Syntax
- Page Extension Object Syntax
- Codeunit Object Syntax

For more information, see []().

## Compiling and Deploying
Extensions are compiled as .navm package files. The .navm package file can be deployed to the NAV server ()... A .navm package contains the various artifacts that deliver the new functionality to the [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] deployment as well as a manifest that specifies the name, publisher, version, and other attributes of the extension. .json file? 

(Future: You manage .navm packages with a series of Windows PowerShell cmdlets that are available in the Microsoft Dynamics NAV 2017 Administration Shell. There are also cmdlets available to ISVs and developers in the Microsoft Dynamics NAV 2017 Development Shell that help create packages.) 

## .NET
 .NET integration?

## Visual Designer
Visual Designer – to work side-by-side with VS Code.


## See Also
[Getting Started Developing for Dynamics 365 for Financials](../dynamics-nav/dyn-fin-geting-started-dev-env.md)  
[Page Extension Object](dyn-fin-page-ext-object.md)  
[Keyboard Shortcuts](dyn-fin-keyboard-shortcuts.md)