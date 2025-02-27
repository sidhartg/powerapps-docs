---
title: DataSet Element | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
author: Nkrb
manager: kvivek
ms.date: 04/23/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: 9ffe8930-b290-4252-98d4-a1195b00205f
---

# data-set element

[!INCLUDE[cc-beta-prerelease-disclaimer](../../../includes/cc-beta-prerelease-disclaimer.md)]

[!INCLUDE [data-set-description](includes/data-set-description.md)]

## Attributes

|Name|Description|Type|Required|
|--|--|--|--|
|`description-key`|Used in the customization screen as localized strings that describes the description of the property.|`string`|Optional|
|`display-name-key`|Used in the customization screens as localized strings that describes the name of the property.|`string`|Yes|
|`name`|Name of the grid|`string`|Yes|

## Parent Elements

|Element|Description|
|--|--|
|[control](control.md)|[!INCLUDE [control-description](includes/control-description.md)]|

## Example

```xml
 <data-set name="dataSetGrid" display-name-key="DataSetGridProperty">
 </data-set>
```

### Related topics

[PowerApps component framework Manifest Schema Reference](index.md)<br/>
[PowerApps component framework API Reference](../reference/index.md)<br/>
[PowerApps component framework Overview](../overview.md)