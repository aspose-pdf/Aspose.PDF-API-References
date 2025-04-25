---
title: ICustomSecurityHandler.EncryptPermissions
second_title: Aspose.PDF for .NET API Reference
description: ICustomSecurityHandler method. Encrypt the documents permissions field. The result will be written to the Perms encryption dictionary field. When opening a document the value can be obtained in EncryptionParameters via the Perms field. Allows you to check if the document permissions have changed
type: docs
weight: 90
url: /net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field. When opening a document, the value can be obtained in [`EncryptionParameters`](../../encryptionparameters/) via the Perms field. Allows you to check if the document permissions have changed.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| permissions | Int32 | The document permissions in integer representation. |

### Return Value

The encrypted array.

### See Also

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


