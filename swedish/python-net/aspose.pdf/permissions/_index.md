---
title: "Behörigheter"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Denna enum representerar användarens behörigheter för en PDF."
type: docs
weight: 6560
url: /sv/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Denna enum representerar användarens behörigheter för en PDF.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| PRINT_DOCUMENT | (Säkerhetshanterare för revision 2) Skriv ut dokumentet.<br/>            (Säkerhetshanterare för revision 3 eller högre) Skriv ut dokumentet <br/>            (möjligen inte på högsta kvalitetsnivå, <br/>            beroende på om [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) också är aktiverad). |
| MODIFY_CONTENT | Ändra dokumentets innehåll genom operationer som inte <br/>            styrs av  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), och 11. |
| EXTRACT_CONTENT | (Säkerhetshanterare för revision 2) Kopiera eller på annat sätt extrahera <br/>            text och grafik från dokumentet, inklusive att extrahera <br/>            text och grafik (för att stödja tillgänglighet för användare <br/>            med funktionsnedsättningar eller för andra ändamål).<br/>            (Säkerhetshanterare för revision 3 eller högre) Kopiera eller på annat sätt <br/>            extrahera text och grafik från dokumentet genom operationer <br/>            som inte styrs av [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält, <br/>            och, om [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) också är aktiverad, skapa eller ändra interaktiva formulär <br/>            fält (inklusive signaturfält). |
| FILL_FORM | (Säkerhetshanterare för revision 3 eller högre) Fyll i befintliga <br/>            interaktiva formulärfält (inklusive signaturfält), även om <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) är avmarkerad. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Säkerhetshanterare för revision 3 eller högre) Extrahera text och <br/>            grafik (för att stödja tillgänglighet för användare med funktionsnedsättningar <br/>            eller för andra ändamål). |
| ASSEMBLE_DOCUMENT | (Säkerhetshanterare för revision 3 eller högre) Sätt ihop dokumentet <br/>            (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) är avmarkerad. |
| PRINTING_QUALITY | (Säkerhetshanterare för revision 3 eller högre) Skriv ut dokumentet till <br/>            en representation från vilken en trogen digital kopia av PDF-innehållet <br/>            kan genereras. När denna bit är avmarkerad (och bit 3 är satt), <br/>            är utskriften begränsad till en låg nivå-representation av utseendet, <br/>            möjligen med försämrad kvalitet. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

