---
title: Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey method
linktitle: GetUserKey
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey method. Creates an encoded array based on the user''s password. This value is typically used to check if the password belongs to the user or owner, and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The user-specified password is passed as an argument when calling document encryption in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler::GetUserKey method


Creates an encoded array based on the user's password. This value is typically used to check if the password belongs to the user or owner, and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The user-specified password is passed as an argument when calling document encryption.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey(System::String userPassword)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | The user password. |

### ReturnValue

The array of user key.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
