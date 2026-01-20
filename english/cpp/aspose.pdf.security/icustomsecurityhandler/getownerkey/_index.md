---
title: Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey method
linktitle: GetOwnerKey
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey method. Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in CalculateEncryptionKey to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler::GetOwnerKey method


Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in [CalculateEncryptionKey](../calculateencryptionkey/) to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey(System::String userPassword, System::String ownerPassword)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | The user password. |
| ownerPassword | System::String | The owner password. |

### ReturnValue

The array of owner key.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
