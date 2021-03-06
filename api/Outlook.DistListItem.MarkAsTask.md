---
title: DistListItem.MarkAsTask Method (Outlook)
keywords: vbaol11.chm3035
f1_keywords:
- vbaol11.chm3035
ms.prod: outlook
api_name:
- Outlook.DistListItem.MarkAsTask
ms.assetid: a8f5a666-95d6-9a97-14bb-ca0b6481e7a8
ms.date: 06/08/2017
---


# DistListItem.MarkAsTask Method (Outlook)

Marks a  **[DistListItem](Outlook.DistListItem.md)** object as a task and assigns a task interval for the object.


## Syntax

 _expression_. `MarkAsTask`( `_MarkInterval_` )

 _expression_ An expression that returns a [DistListItem](./Outlook.DistListItem.md) object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _MarkInterval_|Required| **[OlMarkInterval](Outlook.OlMarkInterval.md)**|The task interval for the  **DistListItem** .|

## Remarks

Calling this method sets the value of several other properties, depending on the value provided in  _MarkInterval_. For more information about the properties set by specifying  _MarkInterval_, see [OlMarkInterval Enumeration](Outlook.OlMarkInterval.md).


## See also


[DistListItem Object](Outlook.DistListItem.md)

