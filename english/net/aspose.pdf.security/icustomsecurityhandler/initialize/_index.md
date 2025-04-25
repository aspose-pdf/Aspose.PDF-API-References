---
title: ICustomSecurityHandler.Initialize
second_title: Aspose.PDF for .NET API Reference
description: ICustomSecurityHandler method. Called to initialize the current instance for encryption. Note that when encrypting it will be filled with the data of the transferred properties ICustomSecurityHandler and when opening the document from the encryption dictionary. If the method is called during new encryption then UserKey and OwnerKey will be null
type: docs
weight: 120
url: /net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Called to initialize the current instance for encryption. Note that when encrypting, it will be filled with the data of the transferred properties [`ICustomSecurityHandler`](../), and when opening the document from the encryption dictionary. If the method is called during new encryption, then [`UserKey`](../../encryptionparameters/userkey/) and [`OwnerKey`](../../encryptionparameters/ownerkey/) will be null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | EncryptionParameters | The encryption parameters. |

### See Also

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


