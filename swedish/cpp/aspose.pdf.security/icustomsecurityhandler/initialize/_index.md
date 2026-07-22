---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Initialize metod"
linktitle: "Initialize"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Initialize metod. Anropas för att initiera den aktuella instansen för kryptering. Observera att vid kryptering kommer den att fyllas med data från de överförda egenskaperna ICustomSecurityHandler, och vid öppning av dokumentet från krypteringsordlistan. Om metoden anropas under ny kryptering, kommer EncryptionParameters::UserKey och EncryptionParameters::OwnerKey att vara null i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler::Initialize method


Anropas för att initiera den aktuella instansen för kryptering. [Note](../../../aspose.pdf/note/) att vid kryptering kommer den att fyllas med data från de överförda egenskaperna [ICustomSecurityHandler](../), och vid öppning av dokumentet från krypteringsordlistan. Om metoden anropas under ny kryptering, kommer [EncryptionParameters::UserKey](../) och [EncryptionParameters::OwnerKey](../) att vara null.

```cpp
virtual void Aspose::Pdf::Security::ICustomSecurityHandler::Initialize(System::SharedPtr<EncryptionParameters> parameters)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | System::SharedPtr\<EncryptionParameters\> | Krypteringsparametrarna. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EncryptionParameters](../../encryptionparameters/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
