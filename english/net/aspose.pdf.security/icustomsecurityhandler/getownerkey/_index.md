---
title: ICustomSecurityHandler.GetOwnerKey
second_title: Aspose.PDF for .NET API Reference
description: ICustomSecurityHandler method. Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in CalculateEncryptionKey to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified
type: docs
weight: 100
url: /net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in [`CalculateEncryptionKey`](../calculateencryptionkey/) to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | The user password. |
| ownerPassword | String | The owner password. |

### Return Value

The array of owner key.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


