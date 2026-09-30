---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
linktitle: "CalculateEncryptionKey"
articleTitle: "CalculateEncryptionKey"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, w..."
type: docs
weight: 50
url: "/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/"
product_version: "26.9.0"
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Calculate the EncryptionKey. Generally the key is calculated based on the UserKey.
 You can use values from EncryptionParams, which contains the current parameters at the time of the call.
 This value is passed as the key argument in `Encrypt` and `Decrypt`.

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | Password entered by the user. |

### Return Value

The array of encryption key.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

