---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar ett absorber‑objekt för sidstrukturobjekt såsom sektioner och stycken.<br/>            Utför sökning efter sektioner och stycken av text och tillhandahåller åtkomst till rektanglar och polygoner som beskriver dem i textkoordinatrymden. <br/>            Utför också sökning av textsegment och tillhandahåller åtkomst till sökresultat via TextFragments‑samlingar grupperade efter strukturelement."
type: docs
weight: 240
url: /sv/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Representerar ett absorber‑objekt för sidstrukturobjekt såsom sektioner och stycken.<br/>            Utför sökning efter sektioner och stycken av text och tillhandahåller åtkomst till rektanglar och polygoner som beskriver dem i textkoordinatrymden. <br/>            Utför också sökning av textsegment och tillhandahåller åtkomst till sökresultat via TextFragments‑samlingar grupperade efter strukturelement.

Typen ParagraphAbsorber exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| ParagraphAbsorber() | Initierar en ny instans av [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) som utför sökning efter sektioner/avsnitt i dokumentet eller på sidan. |
| ParagraphAbsorber(sections_search_depth) | Initierar en ny instans av klassen ParagraphAbsorber |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| page_markups | Hämtar samling av [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) som absorberades. |
| sections_search_depth | Hämtar eller anger värde som bestämmer hur många gånger sekventiella sökningar efter finare strukturelement ska utföras.<br/>            Standard sökdjup är 3.<br/>            Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner). |
| is_multicolumn_paragraphs_allowed | Hämtar eller anger värdet som indikerar om startlinjerna i en nästa sektion kan behandlas som en fortsättning på det sista stycket i en föregående sektion. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| visit(doc) | Utför sökning efter sektioner och stycken i det angivna [Document](/pdf/python-net/aspose.pdf/document/). |
| visit(page) | Utför sökning på den angivna [Page](/pdf/python-net/aspose.pdf/page/). |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

