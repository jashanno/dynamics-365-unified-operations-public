---
# required metadata

title: Workflow subsystem updates in Dynamics 365 for Operations | Microsoft Docs
description: This article reviews the workflow system in Microsoft Dynamics 365 for Operations. It describes the changes that have been implemented since Microsoft Dynamics AX 2012 and also includes links to more information about the workflow system. 
author: sericks007
manager: AnnBe
ms.date: 2015-12-02 20:55:59
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Developer
# ms.devlang: 
ms.reviewer: 61
ms.suite: Released- Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
ms.custom: 13511
ms.assetid: 9bac9218-45dd-456f-a8fd-1a2b1ff5fa71
ms.region: Global
# ms.industry: 
ms.author: tjvass

---

# Workflow subsystem updates in Dynamics 365 for Operations

This article reviews the workflow system in Microsoft Dynamics 365 for Operations. It describes the changes that have been implemented since Microsoft Dynamics AX 2012 and also includes links to more information about the workflow system. 

The workflow system in Dynamics 365 for Operations will already be familiar to you if you've used Microsoft Dynamics AX 2012. For more information about the workflow subsystem in Dynamics AX 2012, see the following topics.

| To learn about this subject | See this topic                                             |
|-----------------------------|------------------------------------------------------------|
| The workflow system         | <http://technet.microsoft.com/en-us/library/dd309672.aspx> |
| Workflow types by module    | <http://technet.microsoft.com/EN-US/library/dd362043.aspx> |
| Workflow elements           | <http://technet.microsoft.com/en-us/library/dd309626.aspx> |
| Workflow actions            | <http://technet.microsoft.com/EN-US/library/dd362144.aspx> |
| Workflow participants       | <http://technet.microsoft.com/EN-US/library/dd309598.aspx> |
| Workflow examples           | <http://technet.microsoft.com/en-us/library/dd309636.aspx> |
| Developing a workflow       | <http://msdn.microsoft.com/EN-US/library/cc967389.aspx>    |
| Implementing a workflow     | <http://msdn.microsoft.com/en-us/library/cc585061.aspx>    |

## Primary changes to the workflow system
Here are the primary changes that have been implemented in Dynamics 365 for Operations:

-   Integration with the new Application State Machine feature enables workflow events to be bound to state transitions on the underlying entity's state machine. This binding enables business logic to be centralized within the state machine and also enables the workflow system to be a declarative consumer of that state machine. The workflow metadata can reference a state transition that is performed when a specific workflow event occurs. Therefore, you can do state transitions within a workflow without writing any additional code.
-   The workflow editor is now a program that you click one time to download. The editor communicates with Dynamics 365 for Operations by using services. Therefore, Dynamics 365 for Operations can carry forward the rich, graphical workflow design experience from Dynamics AX 2012.
-   Workflow development wizards have been ported into Microsoft Visual Studio.


See also
--------

[Technical Concepts Guide for Developers](https://docs.microsoft.com/en-us/dynamics365/operations/dev-itpro/get-started/technical-concepts-guide)
