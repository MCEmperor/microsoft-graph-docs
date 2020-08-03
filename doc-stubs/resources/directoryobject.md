---
title: "directoryObject resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# directoryObject resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List externalSponsors](../api/connectedorganization-list-externalsponsors.md)|[directoryObject](../resources/directoryobject.md) collection|Get the directoryObjects from the externalSponsors navigation property.|
|[Create externalSponsors](../api/connectedorganization-post-externalsponsors.md)|[directoryObject](../resources/directoryobject.md)|Create a new externalSponsors object.|
|[Update externalSponsors](../api/connectedorganization-update-externalsponsors.md)|[directoryObject](../resources/directoryobject.md)|Update the properties of an externalSponsors object.|
|[Get externalSponsors](../api/connectedorganization-get-directoryobject.md)|[directoryObject](../resources/directoryobject.md)|Read the properties and relationships of a [directoryObject](../resources/directoryobject.md) object.|
|[Delete externalSponsors](../api/connectedorganization-delete-externalsponsors.md)|None|Delete a [directoryObject](../resources/directoryobject.md) object.|
|[List directoryObjects](../api/directoryobject-list.md)|[directoryObject](../resources/directoryobject.md) collection|Get a list of the [directoryObject](../resources/directoryobject.md) objects and their properties.|
|[Create directoryObject](../api/directoryobject-create.md)|[directoryObject](../resources/directoryobject.md)|Create a new [directoryObject](../resources/directoryobject.md) object.|
|[Get directoryObject](../api/directoryobject-get.md)|[directoryObject](../resources/directoryobject.md)|Read the properties and relationships of a [directoryObject](../resources/directoryobject.md) object.|
|[Update directoryObject](../api/directoryobject-update.md)|[directoryObject](../resources/directoryobject.md)|Update the properties of a [directoryObject](../resources/directoryobject.md) object.|
|[Delete directoryObject](../api/directoryobject-delete.md)|None|Deletes a [directoryObject](../resources/directoryobject.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.directoryObject",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.directoryObject",
  "id": "String (identifier)"
}
```
