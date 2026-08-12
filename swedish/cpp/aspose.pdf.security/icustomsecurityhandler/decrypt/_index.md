---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt metod"
linktitle: "Dekryptera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt metod. Dekrypterar dataarrayen i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler::Decrypt method


Dekryptera dataarrayen.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Data att dekryptera. |
| objectNumber | int32_t | Nummer på objektet som innehåller den krypterade datan. |
| generation | int32_t | Generering av objektet. |
| nyckel | System::ArrayPtr\<uint8_t\> | Nyckel erhållen av metoden CalculateEncryptionKey |

### ReturnValue

Den dekrypterade datan.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
