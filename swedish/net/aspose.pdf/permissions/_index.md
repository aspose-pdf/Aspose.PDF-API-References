---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Behörigheter enum. Denna enum representerar användares behörigheter för en pdf
type: docs
weight: 8480
url: /sv/net/aspose.pdf/permissions/
---
## Behörighetsuppräkning

Denna enum representerar användarens behörigheter för en pdf.

```csharp
[Flags]
public enum Permissions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | `4` | (Säkerhetshanterare av revision 2) Skriv ut dokumentet. (Säkerhetshanterare av revision 3 eller högre) Skriv ut dokumentet (möjligen inte på den högsta kvalitetsnivån, beroende på om PrintingQuality också är inställt). |
| ModifyContent | `8` | Ändra innehållet i dokumentet genom operationer som inte kontrolleras av ModifyTextAnnotations, FillForm och 11. |
| ExtractContent | `10` | (Säkerhetshanterare av revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive att extrahera text och grafik (till stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). (Säkerhetshanterare av revision 3 eller högre) Kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte kontrolleras av ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Lägg till eller ändra textkommentarer, fyll i interaktiva formulärfält och, om ModifyContent också är inställt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillForm | `100` | (Säkerhetshanterare av revision 3 eller högre) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om ModifyTextAnnotations är klart. |
| ExtractContentWithDisabilities | `200` | (Säkerhetshanterare av revision 3 eller högre) Extrahera text och grafik (till stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). |
| AssembleDocument | `400` | (Säkerhetshanterare av revision 3 eller högre) Sätt ihop dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om ModifyContent är klart. |
| PrintingQuality | `800` | (Säkerhetshanterare av revision 3 eller högre) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF-innehållet kan genereras. När denna bit är klar (och bit 3 är inställd), är utskriften begränsad till en låg nivå av representation av utseendet, möjligen av försämrad kvalitet. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)