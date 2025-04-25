---
title: ICustomSecurityHandler.GetUserKey
second_title: Aspose.PDF for .NET API Reference
description: ICustomSecurityHandler method. Creates an encoded array based on the users password. This value is typically used to check if the password belongs to the user or owner and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The userspecified password is passed as an argument when calling document encryption
type: docs
weight: 110
url: /net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Creates an encoded array based on the user's password. This value is typically used to check if the password belongs to the user or owner, and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The user-specified password is passed as an argument when calling document encryption.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | The user password. |

### Return Value

The array of user key.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


