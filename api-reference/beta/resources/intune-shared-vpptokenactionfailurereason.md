---
title: "vppTokenActionFailureReason enum type"
description: "Possible types of reasons for an Apple Volume Purchase Program token action failure."
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: enumPageType
ms.date: 08/01/2024
---

# vppTokenActionFailureReason enum type

Namespace: microsoft.graph
> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.


Possible types of reasons for an Apple Volume Purchase Program token action failure.

## Members
|Member|Value|Description|
|:---|:---|:---|
|none|0|None.|
|appleFailure|1|There was an error on Apple's service.|
|internalError|2|There was an internal error.|
|expiredVppToken|3|There was an error because the Apple Volume Purchase Program token was expired.|
|expiredApplePushNotificationCertificate|4|There was an error because the Apple Volume Purchase Program Push Notification certificate expired.|
