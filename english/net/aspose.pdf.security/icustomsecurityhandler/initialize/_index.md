---
title: "ICustomSecurityHandler.Initialize"
linktitle: "Initialize"
articleTitle: "Initialize"
second_title: "Aspose.PDF for .NET"
description: "Called to initialize the current instance for encryption. Note that when encrypting, it will be filled with the data of the transferred properties , and when..."
type: docs
weight: 40
url: "/net/aspose.pdf.security/icustomsecurityhandler/initialize/"
product_version: "26.9.0"
---
## Initialize([EncryptionParameters](../../../aspose.pdf.security/encryptionparameters/)) {#initialize}

Called to initialize the current instance for encryption.
 Note that when encrypting, it will be filled with the data of the transferred properties [`ICustomSecurityHandler`](../../../aspose.pdf.security/icustomsecurityhandler/), and when opening the document from the encryption dictionary.
 If the method is called during new encryption, then `UserKey` and `OwnerKey` will be null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | EncryptionParameters | The encryption parameters. |

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

