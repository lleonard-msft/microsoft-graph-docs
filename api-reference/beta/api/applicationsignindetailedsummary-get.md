---
title: "Get applicationSignInDetailedSummary"
description: "Retrieve the properties and relationships of an applicationSignInDetailSummary object."
localization_priority: Normal
author: lleonard-msft
ms.prod: "microsoft-identity-platform"
---

# Get applicationSignInDetailedSummary

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Retrieve the properties and relationships of an [applicationSignInDetailSummary](../resources/applicationsignindetailedsummary.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference.md).

|Permission type                        | Permissions (from least to most privileged)              |
|:--------------------------------------|:---------------------------------------------------------|
|Delegated (work or school account)     | Report.Read.All |
|Delegated (personal Microsoft account) | Not supported. |
|Application                            | Not supported. |

## HTTP request
<!-- { "blockType": "ignored" } -->
``` http
GET /reports/applicationSignInDetailedSummary/{id}
```

## Optional query parameters

This method supports the [OData query parameters](/graph/query-parameters) to help customize the response.

## Request headers

| Name      |Description|
|:----------|:----------|
| Authorization | Bearer {code} |

## Request body
Do not supply a request body for this method.

## Response
If successful, this method returns a `200 OK` response code and an [applicationSignInDetailedSummary](../resources/applicationsignindetailedsummary.md) object in the response body.

## Example

### Request
The following is an example of the request.
<!-- {
  "blockType": "request",
  "name": "get_applicationsignindetailedsummary"
}-->
```http
GET https://graph.microsoft.com/beta/reports/applicationSignInDetailedSummary/<id>
```

### Response
The following is an example of the response. 

>**Note:** The response object shown here might be shortened for readability. All the properties will be returned from an actual call.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.applicationSignInDetailedSummary"
} -->
```http
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 295

{
  "id": "id-value",
  "appId": "appId-value",
  "appDisplayName": "appDisplayName-value",
  "status": {
    "errorCode": 99,
    "failureReason": "failureReason-value",
    "additionalDetails": "additionalDetails-value"
  },
  "signInCount": 99,
  "aggregatedEventDateTime": "datetime-value"
}
```
#### SDK sample code
# [C#](#tab/cs)
[!INCLUDE [sample-code](../includes/get_applicationsignindetailedsummary-Cs-snippets.md)]

# [Javascript](#tab/javascript)
[!INCLUDE [sample-code](../includes/get_applicationsignindetailedsummary-Javascript-snippets.md)]

---

[!INCLUDE [sdk-documentation](../includes/snippets_sdk_documentation_link.md)]

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Get applicationSignInDetailedSummary",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": [
    "Error: /api-reference/beta/api/applicationsignindetailedsummary-get.md:\r\n      BookmarkMissing: '[#tab/cs](C#)'. Did you mean: #c (score: 5)",
    "Error: /api-reference/beta/api/applicationsignindetailedsummary-get.md:\r\n      BookmarkMissing: '[#tab/javascript](Javascript)'. Did you mean: #javascript (score: 4)"
  ]
}-->