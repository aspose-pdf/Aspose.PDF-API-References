---
title: "Klassen Signature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Forms.Signature klass. En abstrakt klass som representerar signaturobjekt i pdf-dokumentet. Signaturer är fält med värden av signaturobjekt som i sin tur innehåller data som används för att verifiera dokumentets giltighet"
type: docs
weight: 5390
url: /sv/net/aspose.pdf.forms/signature/
---
## Signature class

En abstrakt klass som representerar signaturobjekt i pdf-dokumentet. Signaturer är fält med värden av signaturobjekt, där de sista innehåller data som används för att verifiera dokumentets giltighet.

```csharp
public abstract class Signature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Signature](signature/#constructor)() | Initierar en ny instans av `Signature`-klassen. |
| [Signature](signature/#constructor_1)(Stream, string) | Initierar en ny instans av `Signature`-klassen. |
| [Signature](signature/#constructor_2)(string, string) | Initierar en ny instans av `Signature`-klassen. |

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
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_2)(X509Certificate2, ValidationOptions, out ValidationResult) | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet. |

### Se även

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


