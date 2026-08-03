---
title: "Klass ExternalSignature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Forms.ExternalSignature-klass. Skapar en fristående PKCS7-signatur med en X509Certificate2. Den stöder USB-smartkort och token utan exporterbara privata nycklar."
type: docs
weight: 5160
url: /sv/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

```csharp
public class ExternalSignature : Signature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Skapar en fristående PKCS#7 `(detached)`-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | Skapar en PKCS#7-signatur med en X509Certificate2 som base64-sträng. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | Skapar en PKCS#7 `(detached)`-signatur med en X509Certificate2 som base64-sträng. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | Skapar en fristående PKCS#7 `(detached)`-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar. |

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

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | Certifikatet med den privata nyckeln. |

### Se även

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


