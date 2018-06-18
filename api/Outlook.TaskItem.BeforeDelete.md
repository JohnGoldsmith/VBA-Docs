---
title: TaskItem.BeforeDelete Event (Outlook)
ms.prod: outlook
api_name:
- Outlook.TaskItem.BeforeDelete
ms.assetid: bee490b1-2ddb-3942-adfe-ed8051b7b0d8
ms.date: 06/08/2017
---


# TaskItem.BeforeDelete Event (Outlook)

Occurs before an item (which is an instance of the parent object) is deleted.


## Syntax

 _expression_ . **BeforeDelete**( **_Item_** , **_Cancel_** )

 _expression_ A variable that represents a **TaskItem** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Item_|Required| **Object**|The item being deleted.|
| _Cancel_|Required| **Boolean**| **False** when the event occurs. If the event procedure sets this argument to **True** , the operation is not completed and the item is not deleted.|

## Remarks

In order for this event to fire when an e-mail message, distribution list, journal entry, task, contact, or post are deleted through an action, an inspector must be open.

The event occurs each time an item is deleted.


## See also


[TaskItem Object](Outlook.TaskItem.md)
