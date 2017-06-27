﻿#  resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Contains properties, inherited properties and actions for AFW mobile app configurations.

Inherits from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)

## Methods
|Method|Return Type|Description|
|---|---|---|
|[List androidForWorkMobileAppConfigurations](../api/intune_apps_androidforworkmobileappconfiguration_list.md)|[androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md) collection|List properties and relationships of the [androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md) objects.|
|[Get androidForWorkMobileAppConfiguration](../api/intune_apps_androidforworkmobileappconfiguration_get.md)|[androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md)|Read properties and relationships of the [androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md) object.|
|[Create androidForWorkMobileAppConfiguration](../api/intune_apps_androidforworkmobileappconfiguration_create.md)|[androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md)|Create a new [androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md) object.|
|[Delete androidForWorkMobileAppConfiguration](../api/intune_apps_androidforworkmobileappconfiguration_delete.md)|None|Deletes a [androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md).|
|[Update androidForWorkMobileAppConfiguration](../api/intune_apps_androidforworkmobileappconfiguration_update.md)|[androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md)|Update the properties of a [androidForWorkMobileAppConfiguration](../resources/intune_apps_androidforworkmobileappconfiguration.md) object.|
|[List mdmAppConfigGroupAssignments](../api/intune_apps_mdmappconfiggroupassignment_list.md)|[mdmAppConfigGroupAssignment](../resources/intune_apps_mdmappconfiggroupassignment.md) collection|List properties and relationships of the [mdmAppConfigGroupAssignment](../resources/intune_apps_mdmappconfiggroupassignment.md) objects.|
|[List managedDeviceMobileAppConfigurationDeviceStatuses](../api/intune_apps_manageddevicemobileappconfigurationdevicestatus_list.md)|[managedDeviceMobileAppConfigurationDeviceStatus](../resources/intune_apps_manageddevicemobileappconfigurationdevicestatus.md) collection|List properties and relationships of the [managedDeviceMobileAppConfigurationDeviceStatus](../resources/intune_apps_manageddevicemobileappconfigurationdevicestatus.md) objects.|
|[List managedDeviceMobileAppConfigurationUserStatuses](../api/intune_apps_manageddevicemobileappconfigurationuserstatus_list.md)|[managedDeviceMobileAppConfigurationUserStatus](../resources/intune_apps_manageddevicemobileappconfigurationuserstatus.md) collection|List properties and relationships of the [managedDeviceMobileAppConfigurationUserStatus](../resources/intune_apps_manageddevicemobileappconfigurationuserstatus.md) objects.|
|[Get managedDeviceMobileAppConfigurationDeviceSummary](../api/intune_apps_manageddevicemobileappconfigurationdevicesummary_get.md)|[managedDeviceMobileAppConfigurationDeviceSummary](../resources/intune_apps_manageddevicemobileappconfigurationdevicesummary.md)|Read properties and relationships of the [managedDeviceMobileAppConfigurationDeviceSummary](../resources/intune_apps_manageddevicemobileappconfigurationdevicesummary.md) object.|
|[Get managedDeviceMobileAppConfigurationUserSummary](../api/intune_apps_manageddevicemobileappconfigurationusersummary_get.md)|[managedDeviceMobileAppConfigurationUserSummary](../resources/intune_apps_manageddevicemobileappconfigurationusersummary.md)|Read properties and relationships of the [managedDeviceMobileAppConfigurationUserSummary](../resources/intune_apps_manageddevicemobileappconfigurationusersummary.md) object.|

## Properties
|Property|Type|Description|
|---|---|---|
|id|String|Key of the entity. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|targetedMobileApps|String collection|the associated app. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|description|String|Admin provided description of the Device Configuration. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|displayName|String|Admin provided name of the device configuration. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|version|Int32|Version of the device configuration. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|packageName|String|Android For Work app configuration package name.|
|payloadJson|String|Android For Work app configuration JSON payload.|
|permissionActions|[androidPermissionAction](../resources/intune_apps_androidpermissionaction.md) collection|List of Android app permissions and corresponding permission actions.|

## Relationships
|Relationship|Type|Description|
|---|---|---|
|groupAssignments|[mdmAppConfigGroupAssignment](../resources/intune_apps_mdmappconfiggroupassignment.md) collection|the associated group assignments. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|deviceStatuses|[managedDeviceMobileAppConfigurationDeviceStatus](../resources/intune_apps_manageddevicemobileappconfigurationdevicestatus.md) collection|List of ManagedDeviceMobileAppConfigurationDeviceStatus. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|userStatuses|[managedDeviceMobileAppConfigurationUserStatus](../resources/intune_apps_manageddevicemobileappconfigurationuserstatus.md) collection|List of ManagedDeviceMobileAppConfigurationUserStatus. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|deviceStatusSummary|[managedDeviceMobileAppConfigurationDeviceSummary](../resources/intune_apps_manageddevicemobileappconfigurationdevicesummary.md)|App configuration device status summary. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|
|userStatusSummary|[managedDeviceMobileAppConfigurationUserSummary](../resources/intune_apps_manageddevicemobileappconfigurationusersummary.md)|App configuration user status summary. Inherited from [managedDeviceMobileAppConfiguration](../resources/intune_apps_manageddevicemobileappconfiguration.md)|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.androidForWorkMobileAppConfiguration"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.androidForWorkMobileAppConfiguration",
  "id": "String (identifier)",
  "targetedMobileApps": [
    "String"
  ],
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "lastModifiedDateTime": "String (timestamp)",
  "displayName": "String",
  "version": 1024,
  "packageName": "String",
  "payloadJson": "String",
  "permissionActions": [
    {
      "@odata.type": "microsoft.graph.androidPermissionAction",
      "permission": "String",
      "action": "String"
    }
  ]
}
```



