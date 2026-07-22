---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt metod"
linktitle: "Kryptera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt metod. Krypterar dataarrayen i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler::Encrypt method


Kryptera dataarrayen.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Data att kryptera. |
| objectNumber | int32_t | Nummer på objektet som innehåller den krypterade datan. |
| generation | int32_t | Generering av objektet. |
| nyckel | System::ArrayPtr\<uint8_t\> | Nyckel erhållen av metoden CalculateEncryptionKey |

### ReturnValue

Den krypterade datan.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
