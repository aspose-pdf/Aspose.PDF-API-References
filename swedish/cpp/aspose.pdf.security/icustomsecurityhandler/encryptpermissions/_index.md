---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions metod"
linktitle: "EncryptPermissions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions metod. Krypterar dokumentets behörighetsfält. Resultatet skrivs till Perms-fältet i krypteringsordlistan. Vid öppning av ett dokument kan värdet hämtas i EncryptionParameters via Perms-fältet. Gör det möjligt att kontrollera om dokumentbehörigheterna har ändrats i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler::EncryptPermissions method


Kryptera dokumentets behörighetsfält. Resultatet kommer att skrivas till Perms krypteringsordboksfält. När du öppnar ett dokument kan värdet hämtas i [EncryptionParameters](../../encryptionparameters/) via Perms-fältet. Gör det möjligt att kontrollera om dokumentets behörigheter har ändrats.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions(int32_t permissions)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| behörigheter | int32_t | Dokumentets behörigheter i heltalsrepresentation. |

### ReturnValue

Den krypterade arrayen.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
