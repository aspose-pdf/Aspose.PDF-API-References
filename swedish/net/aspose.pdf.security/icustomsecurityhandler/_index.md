---
title: "Interface ICustomSecurityHandler"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Security.ICustomSecurityHandler-interface. Det anpassade säkerhetshanterargränssnittet."
type: docs
weight: 10150
url: /sv/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

Det anpassade säkerhetshanterargränssnittet.

```csharp
public interface ICustomSecurityHandler
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Hämtar filtrens namn. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Hämtar nyckellängden. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Hämtar hanterarens eller krypteringsalgoritmens revision. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Hämtar subfilternamnet. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Hämtar hanterarens eller krypteringsalgoritmens version. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Beräkna EncryptionKey. Vanligtvis beräknas nyckeln baserat på UserKey. Du kan använda värden från EncryptionParams, som innehåller de aktuella parametrarna vid anropstillfället. Detta värde skickas som nyckelargument i [`Encrypt`](./encrypt/) och [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Dekryptera dataarrayen. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Kryptera dataarrayen. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Kryptera dokumentets behörighetsfält. Resultatet kommer att skrivas till Perms-fältet i krypteringsordlistan. När du öppnar ett dokument kan värdet hämtas i [`EncryptionParameters`](../encryptionparameters/) via Perms-fältet. Gör det möjligt att kontrollera om dokumentets behörigheter har ändrats. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Skapar en kodad array baserad på lösenord som kommer att skrivas till O-fältet i krypteringsordlistan. Borde endast förlita sig på de överförda argumenten. Användarlösenordet kan beräknas från detta fält med ägarlösenordet. Anropas under kryptering för att förbereda det och fylla i krypteringsordlistan. Värdet kommer att vara tillgängligt i [`CalculateEncryptionKey`](./calculateencryptionkey/) för att hämta nyckeln från UserKey. Lösenorden som specificerats av användaren när dokumentkryptering anropas kommer att överföras. Lösenord kan vara ospecificerade eller bara ett kan vara specificerat. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Skapar en kodad array baserad på användarens lösenord. Detta värde används vanligtvis för att kontrollera om lösenordet tillhör användaren eller ägaren, och för att hämta krypteringsnyckeln. Anropas under kryptering för att förbereda det och fylla i krypteringsordlistan. Det användarspecificerade lösenordet skickas som ett argument när dokumentkryptering anropas. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Anropas för att initiera den aktuella instansen för kryptering. Observera att vid kryptering kommer den att fyllas med data från de överförda egenskaperna `ICustomSecurityHandler`, och när dokumentet öppnas från krypteringsordlistan. Om metoden anropas under ny kryptering kommer då [`UserKey`](../encryptionparameters/userkey/) och [`OwnerKey`](../encryptionparameters/ownerkey/) att vara null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Kontrollera om lösenordet är dokumentets ägarlösenord. Metoden anropas efter Initialize. Metodanropet används i PDF API. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Kontrollera om lösenordet tillhör användaren (lösenord för att öppna dokumentet). Metoden anropas efter Initialize. Metodanropet används i PDF API. |

### Se även

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


