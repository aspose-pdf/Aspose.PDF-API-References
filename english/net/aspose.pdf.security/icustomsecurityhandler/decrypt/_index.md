---
title: ICustomSecurityHandler.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: ICustomSecurityHandler method. Decrypt the data array
type: docs
weight: 70
url: /net/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler.Decrypt method

Decrypt the data array.

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | Byte[] | Data to decrypt. |
| objectNumber | Int32 | Number of the object containing the encrypted data. |
| generation | Int32 | Generation of the object. |
| key | Byte[] | Key obtained by the CalculateEncryptionKey method |

### Return Value

The decrypted data.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


