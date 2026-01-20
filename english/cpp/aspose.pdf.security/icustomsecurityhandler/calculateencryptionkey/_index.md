---
title: Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey method
linktitle: CalculateEncryptionKey
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey method. Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, which contains the current parameters at the time of the call. This value is passed as the key argument in Encrypt and Decrypt in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler::CalculateEncryptionKey method


Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, which contains the current parameters at the time of the call. This value is passed as the key argument in [Encrypt](../encrypt/) and [Decrypt](../decrypt/).

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey(System::String password)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| password | System::String | Password entered by the user. |

### ReturnValue

The array of encryption key.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
