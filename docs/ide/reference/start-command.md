---
title: "Start Command | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-general"
ms.topic: "conceptual"
f1_keywords: 
  - "debug.start"
helpviewer_keywords: 
  - "Start command"
  - "Debug.Start command"
ms.assetid: dc4e4aa2-b0ab-4e00-92db-6dc3058ddc21
author: "gewarren"
ms.author: "gewarren"
manager: douge
ms.workload: 
  - "multiple"
---
# Start Command
Begins debugging the startup project.  
  
## Syntax  
  
```  
Debug.Start [address]  
```  
  
## Arguments  
 `address`  
 Optional. The address at which the program suspends execution, similar to a breakpoint in source code. This argument is only valid in debug mode.  
  
## Remarks  
 The **Start** command, when executed, performs a RunToCursor operation to the specified address.  
  
## Example  
 This example starts the debugger and ignores any exceptions that occur.  
  
```  
>Debug.Start  
```  
  
## See Also  
 [Visual Studio Commands](../../ide/reference/visual-studio-commands.md)   
 [Command Window](../../ide/reference/command-window.md)   
 [Find/Command Box](../../ide/find-command-box.md)   
 [Visual Studio Command Aliases](../../ide/reference/visual-studio-command-aliases.md)