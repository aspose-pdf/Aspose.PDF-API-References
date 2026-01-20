---
title: Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt method
linktitle: Encrypt
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt method. Encrypt the data array in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler::Encrypt method


Encrypt the data array.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Data to encrypt. |
| objectNumber | int32_t | Number of the object containing the encrypted data. |
| generation | int32_t | Generation of the object. |
| key | System::ArrayPtr\<uint8_t\> | Key obtained by the CalculateEncryptionKey method |

### ReturnValue

The encrypted data.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
