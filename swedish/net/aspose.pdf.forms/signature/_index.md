---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Signature klass. En abstrakt klass som representerar signaturobjektet i pdf-dokumentet. Signaturer är fält med värden av signaturobjekt, de sista innehåller data som används för att verifiera dokumentets giltighet.
type: docs
weight: 5270
url: /sv/net/aspose.pdf.forms/signature/
---
## Signatur klass

En abstrakt klass som representerar signaturobjektet i pdf-dokumentet. Signaturer är fält med värden av signaturobjekt, de sista innehåller data som används för att verifiera dokumentets giltighet.

```csharp
public abstract class Signature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Signature](signature/#constructor)() | Initierar en ny instans av `Signature` klassen. |
| [Signature](signature/#constructor_1)(Stream, string) | Initierar en ny instans av `Signature` klassen. |
| [Signature](signature/#constructor_2)(string, string) | Initierar en ny instans av `Signature` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Namnet på personen eller myndigheten som signerar dokumentet. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Hämtar och ställer in ett alternativ som avgör om längden på en signatur ska uppskattas. |
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
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Verifiera dokumentet angående denna signatur och returnera sant om dokumentet är giltigt eller annars falskt. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Verifiera dokumentet angående denna signatur och returnera sant om dokumentet är giltigt eller annars falskt. |

### Se Även

* namnrymd [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* sammansättning [Aspose.PDF](../../)