---
title: bitsadmin list
description: "Windows Commands topic for **bitsadmin list** - lists the transfer jobs owned by the current user."
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 1416965e-e0e6-49cf-b1d4-b286d3cf8716
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# bitsadmin list

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

lists the transfer jobs owned by the current user.
## Syntax
```
bitsadmin /list [/allusers][/verbose]
```
## Parameters
|Parameter|Description|
|-------|--------|
|/Allusers|Optional lists jobs for all users|
|/verbose|Optional provides detail information for each job.|
## remarks
You must have administrator privileges to use the /allusers parameter
## <a name="BKMK_examples"></a>Examples
The following example retrieves information about jobs owned by the current user.
```
C:\>bitsadmin /list 
```
## additional references
[Command-Line Syntax Key](command-line-syntax-key.md)