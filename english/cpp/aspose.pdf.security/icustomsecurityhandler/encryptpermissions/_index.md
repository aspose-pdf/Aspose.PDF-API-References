---
title: Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions method
linktitle: EncryptPermissions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions method. Encrypt the document''s permissions field. The result will be written to the Perms encryption dictionary field. When opening a document, the value can be obtained in EncryptionParameters via the Perms field. Allows you to check if the document permissions have changed in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler::EncryptPermissions method


Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field. When opening a document, the value can be obtained in [EncryptionParameters](../../encryptionparameters/) via the Perms field. Allows you to check if the document permissions have changed.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions(int32_t permissions)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| permissions | int32_t | The document permissions in integer representation. |

### ReturnValue

The encrypted array.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
