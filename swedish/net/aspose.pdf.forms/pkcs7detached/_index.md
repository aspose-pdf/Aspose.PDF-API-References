---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7Detached klass. Representerar PKCS7-objektet som följer PKCS7-specifikationen i Internet RFC 2315 PKCS 7 Kryptografisk Meddelandesyntax Version 1.5. Den ursprungliga signerade meddelandets digest över dokumentets byte-intervall är inbäddad som det normala PKCS7 SignedData-fältet. Inga data ska inneslutas i PKCS7 SignedData-fältet.
type: docs
weight: 5190
url: /sv/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached klass

Representerar PKCS#7-objektet som följer PKCS#7-specifikationen i Internet RFC 2315, PKCS #7: Kryptografisk Meddelandesyntax, Version 1.5. Den ursprungliga signerade meddelandets digest över dokumentets byte-intervall är inbäddad som det normala PKCS#7 SignedData-fältet. Inga data ska inneslutas i PKCS#7 SignedData-fältet.

```csharp
public sealed class PKCS7Detached : Signature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached` klassen. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Initierar en ny instans av `PKCS7Detached` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Namnet på personen eller myndigheten som signerar dokumentet. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Hämtar och ställer in ett alternativ som innebär om man ska undvika att uppskatta längden på en signatur. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | En array av par av heltal (startbyte-offset, längd i byte) som ska beskriva det exakta byte-intervall för digestberäkningen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Information som tillhandahålls av signatären för att möjliggöra för en mottagare att kontakta signatären för att verifiera signaturen, t.ex. ett telefonnummer. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Hämtar/ställer in den anpassade utseendet. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Delegaten för att anpassa signaturen av dokumentets hash. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Tidpunkten för signeringen. |
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
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifierar dokumentet angående denna signatur och returnerar sant om dokumentet är giltigt eller annars falskt. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifierar dokumentet angående denna signatur och returnerar sant om dokumentet är giltigt eller annars falskt. |

### Se Även

* klass [Signature](../signature/)
* namnrymd [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)