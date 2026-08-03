---
title: "Enum Permissions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Permissions enum. Detta enum representerar användarbehörigheter för en pdf"
type: docs
weight: 8610
url: /sv/net/aspose.pdf/permissions/
---
## Permissions enumeration

Denna enum representerar användarens behörigheter för en pdf.

```csharp
[Flags]
public enum Permissions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | `4` | (Säkerhetshanterare för revision 2) Skriv ut dokumentet. (Säkerhetshanterare för revision 3 eller högre) Skriv ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på om PrintingQuality också är inställd). |
| ModifyContent | `8` | Ändra dokumentets innehåll med operationer som inte styrs av ModifyTextAnnotations, FillForm och 11. |
| ExtractContent | `10` | (Säkerhetshanterare för revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive att extrahera text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). (Säkerhetshanterare för revision 3 eller högre) Kopiera eller på annat sätt extrahera text och grafik från dokumentet med operationer som inte styrs av ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält och, om ModifyContent också är aktiverat, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillForm | `100` | (Säkerhetshanterare för revision 3 eller högre) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om ModifyTextAnnotations är avaktiverat. |
| ExtractContentWithDisabilities | `200` | (Säkerhetshanterare för revision 3 eller högre) Extrahera text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). |
| AssembleDocument | `400` | (Säkerhetshanterare för revision 3 eller högre) Sätt ihop dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om ModifyContent är avaktiverat. |
| PrintingQuality | `800` | (Säkerhetshanterare för revision 3 eller högre) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF‑innehållet kan genereras. När den här biten är avaktiverad (och bit 3 är aktiverad) begränsas utskriften till en låg‑nivå representation av utseendet, möjligen med försämrad kvalitet. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


