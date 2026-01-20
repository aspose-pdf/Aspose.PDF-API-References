---
title: Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt method
linktitle: Decrypt
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt method. Decrypt the data array in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler::Decrypt method


Decrypt the data array.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Data to decrypt. |
| objectNumber | int32_t | Number of the object containing the encrypted data. |
| generation | int32_t | Generation of the object. |
| key | System::ArrayPtr\<uint8_t\> | Key obtained by the CalculateEncryptionKey method |

### ReturnValue

The decrypted data.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
