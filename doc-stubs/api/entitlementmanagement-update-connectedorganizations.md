---
title: "Update connectedOrganizations"
description: "Update the properties of a connectedOrganizations object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update connectedOrganizations
Namespace: microsoft.graph

Update the properties of a connectedOrganizations object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /identityGovernance/entitlementManagement/connectedOrganizations
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [connectedOrganization](../resources/connectedorganization.md) object.

The following table shows the properties that are required when you create the [connectedOrganization](../resources/connectedorganization.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|identitySources|[identitySource](../resources/identitysource.md) collection|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [connectedOrganization](../resources/connectedorganization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_connectedorganizations"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/connectedOrganizations
Content-Type: application/json
Content-length: 283

{
  "@odata.type": "#microsoft.graph.connectedOrganization",
  "displayName": "String",
  "description": "String",
  "createdBy": "String",
  "modifiedBy": "String",
  "identitySources": [
    {
      "@odata.type": "microsoft.graph.azureActiveDirectoryTenant"
    }
  ]
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.connectedOrganization",
  "id": "eb866cdc-6cdc-eb86-dc6c-86ebdc6c86eb",
  "displayName": "String",
  "description": "String",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)",
  "identitySources": [
    {
      "@odata.type": "microsoft.graph.azureActiveDirectoryTenant"
    }
  ]
}
```
