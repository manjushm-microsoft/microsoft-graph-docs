﻿# resetPasscodeActionResult resource type

> **Important**: APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Reset passcode action result

Inherits from [deviceActionResult](../resources/intune_devicefe_deviceactionresult.md)

## Properties
|Property|Type|Description|
|---|---|---|
|actionName|String|Action name Inherited from [deviceActionResult](../resources/intune_devicefe_deviceactionresult.md)|
|actionState|String|State of the action Inherited from [deviceActionResult](../resources/intune_devicefe_deviceactionresult.md) Possible values are: `none`, `pending`, `canceled`, `active`, `done`, `failed`, `notSupported`.|
|startDateTime|DateTimeOffset|Time the action was initiated Inherited from [deviceActionResult](../resources/intune_devicefe_deviceactionresult.md)|
|lastUpdatedDateTime|DateTimeOffset|Time the action state was last updated Inherited from [deviceActionResult](../resources/intune_devicefe_deviceactionresult.md)|
|passcode|String|Newly generated passcode for the device |

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.resetPasscodeActionResult"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.resetPasscodeActionResult",
  "actionName": "String",
  "actionState": "String",
  "startDateTime": "String (timestamp)",
  "lastUpdatedDateTime": "String (timestamp)",
  "passcode": "String"
}
```



