---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey metod"
linktitle: "CalculateEncryptionKey"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey metod. Beräkna EncryptionKey. Vanligtvis beräknas nyckeln baserat på UserKey. Du kan använda värden från EncryptionParams, som innehåller de aktuella parametrarna vid anropstillfället. Detta värde skickas som nyckelargument i Encrypt och Decrypt i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler::CalculateEncryptionKey method


Beräkna EncryptionKey. Vanligtvis beräknas nyckeln baserat på UserKey. Du kan använda värden från EncryptionParams, som innehåller de aktuella parametrarna vid anropstillfället. Detta värde skickas som nyckelargument i [Encrypt](../encrypt/) och [Decrypt](../decrypt/).

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey(System::String password)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | System::String | Lösenord som angivits av användaren. |

### ReturnValue

Arrayen med krypteringsnyckeln.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
