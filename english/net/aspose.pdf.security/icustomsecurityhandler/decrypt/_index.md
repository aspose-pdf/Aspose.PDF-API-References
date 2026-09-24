---
title: "ICustomSecurityHandler.Decrypt"
linktitle: "Decrypt"
articleTitle: "Decrypt"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Decrypt the data array."
type: docs
weight: 70
url: "/net/aspose.pdf.security/icustomsecurityhandler/decrypt/"
product_version: "26.9.0"
---
## Decrypt(byte[], int, int, byte[]) {#decrypt}

Decrypt the data array.

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Data to decrypt. |
| objectNumber | int | Number of the object containing the encrypted data. |
| generation | int | Generation of the object. |
| key | byte[] | Key obtained by the CalculateEncryptionKey method |

### Return Value

byte[]

The decrypted data.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

