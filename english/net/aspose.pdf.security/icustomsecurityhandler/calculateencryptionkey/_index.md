---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
linktitle: "CalculateEncryptionKey"
articleTitle: "CalculateEncryptionKey"
second_title: "Aspose.PDF for .NET"
description: "Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, which contains the current param..."
type: docs
weight: 50
url: "/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/"
product_version: "26.9.0"
---
## CalculateEncryptionKey(string) {#calculateencryptionkey}

Calculate the EncryptionKey. Generally the key is calculated based on the UserKey.
 You can use values from EncryptionParams, which contains the current parameters at the time of the call.
 This value is passed as the key argument in `Encrypt` and `Decrypt`.

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | string | Password entered by the user. |

### Return Value

byte[]

The array of encryption key.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

