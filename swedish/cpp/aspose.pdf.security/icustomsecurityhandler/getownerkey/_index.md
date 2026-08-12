---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey metod"
linktitle: "GetOwnerKey"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey metod. Skapar en kodad array baserad på lösenord som kommer att skrivas till O-fältet i krypteringsordboken. Bör endast förlita sig på de överförda argumenten. Användarlösenordet kan beräknas från detta fält med ägarlösenordet. Kallas under kryptering för att förbereda och fylla i krypteringsordboken. Värdet kommer att vara tillgängligt i CalculateEncryptionKey för att hämta nyckeln från UserKey. Lösenorden som specificerats av användaren vid anrop av dokumentkryptering kommer att överföras. Lösenord kan vara ospecificerade eller endast ett kan vara specificerat i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler::GetOwnerKey method


Skapar en kodad array baserad på lösenord som kommer att skrivas till O-fältet i krypteringsordboken. Bör endast förlita sig på de överförda argumenten. Användarlösenordet kan beräknas från detta fält med ägarlösenordet. Kallas under kryptering för att förbereda och fylla i krypteringsordboken. Värdet kommer att vara tillgängligt i [CalculateEncryptionKey](../calculateencryptionkey/) för att hämta nyckeln från UserKey. Lösenorden som specificerats av användaren vid anrop av dokumentkryptering kommer att överföras. Lösenord kan vara ospecificerade eller endast ett kan vara specificerat.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey(System::String userPassword, System::String ownerPassword)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | System::String | Användarlösenordet. |
| ownerPassword | System::String | Ägarlösenordet. |

### ReturnValue

Arrayen med ägarnyckeln.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
