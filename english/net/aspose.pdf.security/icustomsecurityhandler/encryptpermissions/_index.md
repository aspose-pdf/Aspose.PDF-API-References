---
title: "ICustomSecurityHandler.EncryptPermissions"
linktitle: "EncryptPermissions"
articleTitle: "EncryptPermissions"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field. When opening a ..."
type: docs
weight: 10
url: "/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/"
product_version: "26.9.0"
---
## ICustomSecurityHandler.EncryptPermissions method

Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field.
 When opening a document, the value can be obtained in [`EncryptionParameters`](../../../aspose.pdf.security/encryptionparameters/) via the Perms field.
 Allows you to check if the document permissions have changed.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| permissions | Int32 | The document permissions in integer representation. |

### Return Value

The encrypted array.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

