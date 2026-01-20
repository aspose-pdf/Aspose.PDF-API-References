---
title: Aspose::Pdf::Security::ICustomSecurityHandler::Initialize method
linktitle: Initialize
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::Initialize method. Called to initialize the current instance for encryption. Note that when encrypting, it will be filled with the data of the transferred properties ICustomSecurityHandler, and when opening the document from the encryption dictionary. If the method is called during new encryption, then EncryptionParameters::UserKey and EncryptionParameters::OwnerKey will be null in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler::Initialize method


Called to initialize the current instance for encryption. [Note](../../../aspose.pdf/note/) that when encrypting, it will be filled with the data of the transferred properties [ICustomSecurityHandler](../), and when opening the document from the encryption dictionary. If the method is called during new encryption, then [EncryptionParameters::UserKey](../) and [EncryptionParameters::OwnerKey](../) will be null.

```cpp
virtual void Aspose::Pdf::Security::ICustomSecurityHandler::Initialize(System::SharedPtr<EncryptionParameters> parameters)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| parameters | System::SharedPtr\<EncryptionParameters\> | The encryption parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EncryptionParameters](../../encryptionparameters/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
