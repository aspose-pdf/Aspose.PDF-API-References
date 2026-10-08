---
title: "ICustomSecurityHandler.Encrypt"
linktitle: "Encrypt"
articleTitle: "Encrypt"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Encrypt the data array."
type: docs
weight: 60
url: "/net/aspose.pdf.security/icustomsecurityhandler/encrypt/"
product_version: "26.9"
---
## ICustomSecurityHandler.Encrypt method

Encrypt the data array.

```csharp
public byte[] Encrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | Byte[] | Data to encrypt. |
| objectNumber | Int32 | Number of the object containing the encrypted data. |
| generation | Int32 | Generation of the object. |
| key | Byte[] | Key obtained by the CalculateEncryptionKey method |

### Return Value

The encrypted data.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

