---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey metod"
linktitle: "GetUserKey"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey metod. Skapar en kodad array baserad på användarens lösenord. Detta värde används vanligtvis för att kontrollera om lösenordet tillhör användaren eller ägaren, och för att hämta krypteringsnyckeln. Anropas under kryptering för att förbereda den och fylla i krypteringsordlistan. Det användarspecificerade lösenordet skickas som ett argument när dokumentkryptering anropas i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler::GetUserKey method


Skapar en kodad array baserad på användarens lösenord. Detta värde används vanligtvis för att kontrollera om lösenordet tillhör användaren eller ägaren, och för att hämta krypteringsnyckeln. Anropas under kryptering för att förbereda och fylla i krypteringsordboken. Det användarspecificerade lösenordet skickas som argument vid dokumentkryptering.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey(System::String userPassword)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | System::String | Användarlösenordet. |

### ReturnValue

Arrayen med användarnyckel.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
