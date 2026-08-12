---
title: "Aspose::Pdf::Security::ICustomSecurityHandler klass"
linktitle: "ICustomSecurityHandler"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ICustomSecurityHandler klass. Det anpassade säkerhetshanterargränssnittet i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler class


Det anpassade säkerhetshanterargränssnittet.

```cpp
class ICustomSecurityHandler : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CalculateEncryptionKey](./calculateencryptionkey/)(System::String) | Beräkna EncryptionKey. Vanligtvis beräknas nyckeln baserat på UserKey. Du kan använda värden från EncryptionParams, som innehåller de aktuella parametrarna vid anropet. Detta värde skickas som nyckelargument i [Encrypt](./encrypt/) och [Decrypt](./decrypt/). |
| virtual [Decrypt](./decrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Dekryptera dataarrayen. |
| virtual [Encrypt](./encrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Kryptera dataarrayen. |
| virtual [EncryptPermissions](./encryptpermissions/)(int32_t) | Kryptera dokumentets behörighetsfält. Resultatet kommer att skrivas till fältet Perms i krypteringsordboken. När ett dokument öppnas kan värdet hämtas i [EncryptionParameters](../encryptionparameters/) via Perms‑fältet. Gör det möjligt att kontrollera om dokumentets behörigheter har ändrats. |
| virtual [get_Filter](./get_filter/)() | Hämtar filternamnet. |
| virtual [get_KeyLength](./get_keylength/)() | Hämtar nyckellängden. |
| virtual [get_Revision](./get_revision/)() | Hämtar hanteraren eller krypteringsalgoritmens revision. |
| virtual [get_SubFilter](./get_subfilter/)() | Hämtar subfilternamnet. |
| virtual [get_Version](./get_version/)() | Hämtar hanteraren eller krypteringsalgoritmens version. |
| virtual [GetOwnerKey](./getownerkey/)(System::String, System::String) | Skapar en kodad array baserad på lösenord som kommer att skrivas till O‑fältet i krypteringsordboken. Borde endast förlita sig på de överförda argumenten. Användarlösenordet kan beräknas från detta fält med ägarlösenordet. Anropas under kryptering för att förbereda och fylla i krypteringsordboken. Värdet kommer att vara tillgängligt i [CalculateEncryptionKey](./calculateencryptionkey/) för att hämta nyckeln från UserKey. Lösenorden som specificerats av användaren vid dokumentkryptering kommer att överföras. Lösenord kan vara ospecificerade eller endast ett kan specificeras. |
| virtual [GetUserKey](./getuserkey/)(System::String) | Skapar en kodad array baserad på användarens lösenord. Detta värde används vanligtvis för att kontrollera om lösenordet tillhör användaren eller ägaren, och för att hämta krypteringsnyckeln. Anropas under kryptering för att förbereda och fylla i krypteringsordboken. Det användarspecificerade lösenordet skickas som argument vid dokumentkryptering. |
| virtual [Initialize](./initialize/)(System::SharedPtr\<EncryptionParameters\>) | Anropas för att initiera den aktuella instansen för kryptering. [Note](../../aspose.pdf/note/) att vid kryptering kommer den att fyllas med data från de överförda egenskaperna [ICustomSecurityHandler](./), och vid öppning av dokumentet från krypteringsordboken. Om metoden anropas under ny kryptering, kommer då [EncryptionParameters::UserKey](../) och [EncryptionParameters::OwnerKey](../) att vara null. |
| virtual [IsOwnerPassword](./isownerpassword/)(System::String) | Kontrollera om lösenordet är dokumentets ägarlösenord. Metoden anropas efter Initialize. Metodanropet används i PDF‑API:et. |
| virtual [IsUserPassword](./isuserpassword/)(System::String) | Kontrollera om lösenordet tillhör användaren (lösenord för att öppna dokumentet). Metoden anropas efter Initialize. Metodanropet används i PDF‑API:et. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
