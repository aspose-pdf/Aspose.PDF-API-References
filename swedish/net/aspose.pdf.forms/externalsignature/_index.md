---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ExternalSignature klass. Skapar en fristående PKCS7-signatur med hjälp av en X509Certificate2. Den stöder usb smartcards tokens utan exportabla privata nycklar
type: docs
weight: 5040
url: /sv/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature klass

Skapar en fristående PKCS#7-signatur med hjälp av en X509Certificate2. Den stöder usb smartcards, tokens utan exportabla privata nycklar.

```csharp
public class ExternalSignature : Signature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Skapar en fristående PKCS#7 `(detached)` signatur med hjälp av en X509Certificate2. Den stöder usb smartcards, tokens utan exportabla privata nycklar. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | Skapar en PKCS#7 signatur med hjälp av en X509Certificate2 som base64-sträng. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | Skapar en PKCS#7 `(detached)` signatur med hjälp av en X509Certificate2 som base64-sträng. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | Skapar en fristående PKCS#7 signatur med hjälp av en X509Certificate2. Den stöder usb smartcards, tokens utan exportabla privata nycklar. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | Skapar en fristående PKCS#7 `(detached)` signatur med hjälp av en X509Certificate2. Den stöder usb smartcards, tokens utan exportabla privata nycklar. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Namnet på personen eller myndigheten som signerar dokumentet. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Hämtar och ställer in ett alternativ som innebär om man ska undvika att uppskatta längden på en signatur. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | En array av par av heltal (startbyteoffset, längd i byte) som ska beskriva det exakta byteintervallet för digestberäkningen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Information som tillhandahålls av signatären för att möjliggöra för en mottagare att kontakta signatären för att verifiera signaturen, t.ex. ett telefonnummer. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Hämtar/ställer in den anpassade utseendet. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Delegaten för att anpassa signaturen av dokumenthashen. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Tiden för signeringen. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Hämtar eller ställer in standardlängden för signaturdata i byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | CPU-värdnamn eller fysisk plats för signeringen. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Hämtar/ställer in ocsp-inställningar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Anledningen till signeringen, såsom (Jag godkänner, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Tvinga att visa/dölja signaturens egenskaper. Om ShowProperties är sant har signaturfältet ett fördefinierat format av utseende (strängar att representera): ------------------------------------------- Digitalt signerad av {certifikatets ämne} Datum: {signature.Date} Anledning: {signature.Reason} Plats: {signature.Location} ------------------------------------------- där {X} är en platshållare för X-värdet. Signaturen kan också ha en bild, i så fall placeras de listade strängarna över bilden. ShowProperties är sant som standard. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Hämtar/ställer in tidsstämpelinställningar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Hämtar/ställer in ltv-valideringsflagga. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Hämtar information om signaturalgoritmen som används i signaturen. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifiera dokumentet angående denna signatur och returnera sant om dokumentet är giltigt eller annars falskt. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifiera dokumentet angående denna signatur och returnera sant om dokumentet är giltigt eller annars falskt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | Certifikatet med den privata nyckeln. |

### Se Även

* klass [Signature](../signature/)
* namnrymd [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)