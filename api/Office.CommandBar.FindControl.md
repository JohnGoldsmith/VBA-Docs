---
title: CommandBar.FindControl Method (Office)
keywords: vbaof11.chm3006
f1_keywords:
- vbaof11.chm3006
ms.prod: office
api_name:
- Office.CommandBar.FindControl
ms.assetid: d5ff45de-a356-0dab-4233-88326d08535a
ms.date: 06/08/2017
---


# CommandBar.FindControl Method (Office)

Gets a  **CommandBarControl** object that fits a specified criteria.

> [!NOTE]
> The use of CommandBars in some Microsoft Office applications has been superseded by the new ribbon component of the Microsoft Office Fluent user interface. For more information, search Help for the keyword "ribbon."


## Syntax

 _expression_. `FindControl`( `_Type_`, `_Id_`, `_Tag_`, `_Visible_`, `_Recursive_` )

 _expression_ A variable that represents a [CommandBar](./Office.CommandBar.md) object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Type_|Optional|**Variant**|The type of control.|
| _Id_|Optional|**Variant**|The identifier of the control.|
| _Tag_|Optional|**Variant**|The tag value of the control.|
| _Visible_|Optional|**Variant**|True to include only visible command bar controls in the search. The default value is False. Visible command bars include all visible toolbars and any menus that are open at the time the  **FindControl** method is executed.|
| _Recursive_|Optional|**Variant**|True to include the command bar and all of its pop-up subtoolbars in the search. This argument only applies to the  **CommandBar** object. The default value is False.|

## Return value

CommandBarControl


## Remarks

If the  **CommandBars** collection contains two or more controls that fit the search criteria, FindControl returns the first control that's found. If no control that fits the criteria is found, **FindControl** returns Nothing.


## See also


[CommandBar Object](Office.CommandBar.md)



[CommandBar Object Members](./overview/Library-Reference/commandbar-members-office.md)

