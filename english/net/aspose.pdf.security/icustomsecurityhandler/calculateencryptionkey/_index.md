---
title: ICustomSecurityHandler.CalculateEncryptionKey
second_title: Aspose.PDF for .NET API Reference
description: ICustomSecurityHandler method. Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams which contains the current parameters at the time of the call. This value is passed as the key argument in Encrypt and Decrypt
type: docs
weight: 60
url: /net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, which contains the current parameters at the time of the call. This value is passed as the key argument in [`Encrypt`](../encrypt/) and [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | Password entered by the user. |

### Return Value

The array of encryption key.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


