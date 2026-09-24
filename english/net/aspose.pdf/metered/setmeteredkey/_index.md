---
title: "Metered.SetMeteredKey"
linktitle: "SetMeteredKey"
articleTitle: "SetMeteredKey"
second_title: "Aspose.PDF for .NET API Reference"
description: "Metered method. Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is en..."
type: docs
weight: 20
url: "/net/aspose.pdf/metered/setmeteredkey/"
product_version: "26.9.0"
---
## SetMeteredKey(string, string) {#setmeteredkey}

Sets metered public and private key.
 If you purchase metered license, when start application, this API should be called, normally, this is enough. 
 However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, 
 to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | string | public key |
| privateKey | string | private key |

### See Also

* class [Metered](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

