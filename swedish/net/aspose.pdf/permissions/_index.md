---
title: Permissions
second_title: Aspose.PDF för .NET API Referens
description: Denna uppräkning representerar användarens behörigheter för en pdf.
type: docs
weight: 6110
url: /sv/net/aspose.pdf/permissions/
---
## Permissions enumeration

Denna uppräkning representerar användarens behörigheter för en pdf.

```csharp
[Flags]
public enum Permissions
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | `4` | (Säkerhetshanterare av revision 2) Skriv ut dokumentet. (Säkerhetshanterare av revision 3 eller högre) Skriv ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på omPrintingQualityär också inställd). |
| ModifyContent | `8` | Ändra innehållet i dokumentet genom andra operationer än de som kontrolleras avModifyTextAnnotations , FillForm , och 11. |
| ExtractContent | `10` | (Säkerhetshanterare av revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive extrahering av text och grafik (till stöd för tillgänglighet för användare med funktionshinder eller för andra ändamål). (Säkerhetshanterare av revision 3 eller hanterare av revision 3 större) Kopiera eller på annat sätt extrahera text och grafik från dokumentet med andra operationer än de som kontrolleras avExtractContentWithDisabilities . |
| ModifyTextAnnotations | `20` | Lägg till eller ändra textkommentarer, fyll i interaktiva formulärfält, och, omModifyContent ställs också in, skapa eller ändra interaktiva formulär fält (inklusive signaturfält). |
| FillForm | `100` | (Säkerhetshanterare av version 3 eller senare) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om ModifyTextAnnotations är klar. |
| ExtractContentWithDisabilities | `200` | (Säkerhetshanterare av version 3 eller senare) Extrahera text och grafik (till stöd för tillgänglighet för användare med funktionshinder eller för andra ändamål). |
| AssembleDocument | `400` | (Säkerhetshanterare av version 3 eller senare) Sätt ihop dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder ), även omModifyContent är klar. |
| PrintingQuality | `800` | (Säkerhetshanterare av version 3 eller senare) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF-innehållet kan genereras. När denna bit är klar (och bit 3 är inställd) begränsas -utskrift till en lågnivårepresentation av utseendet, möjligen av försämrad kvalitet. |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->