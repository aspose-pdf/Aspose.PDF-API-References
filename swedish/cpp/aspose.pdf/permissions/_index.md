---
title: "Aspose::Pdf::Permissions enum"
linktitle: "Behörigheter"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Permissions enum. Denna enum representerar användarens behörigheter för en pdf i C++."
type: docs
weight: 26000
url: /sv/cpp/aspose.pdf/permissions/
---
## Permissions enum


Denna enum representerar användarens behörigheter för en pdf.

```cpp
enum class Permissions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | n/a | ([Security](../../aspose.pdf.security/) hanterare av revision 2) Skriv ut dokumentet. ([Security](../../aspose.pdf.security/) hanterare av revision 3 eller högre) Skriv ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på om [PrintingQuality](./) också är inställd). |
| ModifyContent | n/a | Ändra dokumentets innehåll genom operationer som inte kontrolleras av [ModifyTextAnnotations](./), [FillForm](./) och 11. |
| ExtractContent | n/a | ([Security](../../aspose.pdf.security/) hanterare av revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive att extrahera text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). ([Security](../../aspose.pdf.security/) hanterare av revision 3 eller högre) Kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte kontrolleras av [ExtractContentWithDisabilities](./). |
| ModifyTextAnnotations | n/a | Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält och, om [ModifyContent](./) också är aktiverad, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillForm | n/a | ([Security](../../aspose.pdf.security/) hanterare av revision 3 eller högre) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om [ModifyTextAnnotations](./) är avmarkerad. |
| ExtractContentWithDisabilities | n/a | ([Security](../../aspose.pdf.security/) hanterare av revision 3 eller högre) Extrahera text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). |
| AssembleDocument | n/a | ([Security](../../aspose.pdf.security/) hanterare av revision 3 eller högre) Sätt ihop dokumentet (infoga, rotera eller radera sidor och skapa bokmärken eller miniatyrbilder), även om [ModifyContent](./) är avmarkerad. |
| PrintingQuality | n/a | ([Security](../../aspose.pdf.security/) hanterare av revision 3 eller högre) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF-innehållet kan genereras. När denna bit är avmarkerad (och bit 3 är satt) begränsas utskriften till en låg nivå-representation av utseendet, möjligen med försämrad kvalitet. |

## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
