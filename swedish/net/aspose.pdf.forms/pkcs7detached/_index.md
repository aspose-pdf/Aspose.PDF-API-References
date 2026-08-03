---
title: "Klass PKCS7Detached"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Forms.PKCS7Detached-klass. Representerar PKCS7-objektet som följer PKCS7-specifikationen i Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5. Det ursprungliga signerade meddelande-digestet över dokumentens byteintervall inkluderas som det normala PKCS7 SignedData-fältet. Ingen data skall kapslas in i PKCS7 SignedData-fältet."
type: docs
weight: 5310
url: /sv/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

Representerar PKCS#7-objektet som följer PKCS#7-specifikationen i Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, version 1.5. Den ursprungliga signerade meddelandedigesten över dokumentets byteintervall införlivas som det normala PKCS#7 SignedData-fältet. Ingen data kapslas in i PKCS#7 SignedData-fältet.

```csharp
public sealed class PKCS7Detached : Signature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached`-klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Namnet på personen eller myndigheten som signerar dokumentet. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Hämtar och anger ett alternativ som avgör om man ska undvika att uppskatta längden på en signatur. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | En array av heltalpar (startbyteoffset, längd i byte) som ska beskriva det exakta byteintervallet för digestberäkningen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Information som tillhandahålls av undertecknaren för att möjliggöra att mottagaren kan kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Hämtar/anger det anpassade utseendet. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Delegaten för att anpassat signera dokumenthashen. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Tidpunkten för signering. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Hämtar eller anger standardlängden för signaturdata i byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | CPU-värdnamnet eller den fysiska platsen för signeringen. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Hämtar/anger OCSP-inställningar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Anledningen till signeringen, till exempel (Jag samtycker, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Tvingar att visa/dölja signaturens egenskaper. Om ShowProperties är true har signaturfältet ett fördefinierat format för utseende (strängar att representera): ------------------------------------------- Digitalt signerat av {certificate subject} Datum: {signature.Date} Orsak: {signature.Reason} Plats: {signature.Location} ------------------------------------------- där {X} är en platshållare för X‑värdet. Signaturen kan också ha en bild; i så fall placeras de listade strängarna över bilden. ShowProperties är true som standard. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Hämtar/anger tidsstämpelinställningar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Hämtar/anger LTV-valideringsflagga. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Hämtar information om signaturalgoritmen som används i signaturen. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet. |

### Se även

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


