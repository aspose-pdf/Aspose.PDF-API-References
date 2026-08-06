---
title: "EpubLoadOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Innehåller alternativ för att läsa in / importera EPUB-fil till pdf-dokument."
type: docs
weight: 310
url: /sv/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Innehåller alternativ för att läsa in / importera EPUB-fil till pdf-dokument.

Typen EpubLoadOptions visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| EpubLoadOptions() | Skapar standardinläsningsalternativ för konvertering av EPUB-fil till PDF-dokument. <br/>            Standard PDF-sidstorlek - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | Initierar en ny instans av klassen EpubLoadOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värde som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |
| load_format | Representerar filformat som [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beskriver. |
| page_size | Hämtar eller anger utskrifts sidstorlek för import. |
| margin | Hämtar referens till objekt som representerar marginalinformation. |
| margins_area_usage_mode | Representerar användningsläge för marginalområdet – definierar behandling <br/>              av instruktioner (om några) i CSS för importerat dokument<br/>              relaterade till användning av marginaler. |
| page_size_adjustment_mode | OBS! Funktionen har implementerats men har ännu inte lagts till i det offentliga API:t på grund av ett blockerande problem i <br/>              OSHARED‑lagret som upptäcktes för exempel‑dokumentet.<br/>              <br/>             <br/>              Representerar läge för användning av sidstorlek under konvertering.<br/>             Format (som HTML, EPUB etc.) har vanligtvis flytande design, så de tillåter att anpassa den erforderliga<br/>             sidstorleken. Men ibland har innehållet specificerade horisontella positioner eller storlek som <br/>             inte tillåter att placera innehållet i den önskade sidstorleken.<br/>               I sådant fall kan vi definiera vad som ska göras i detta scenario (dvs. när innehållets storlek inte passar <br/>             den initiala sidstorleken för det resulterande PDF‑dokumentet). |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

