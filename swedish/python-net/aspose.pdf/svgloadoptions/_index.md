---
title: "SvgLoadOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar alternativ för inläsning/import av SVG-fil i pdf-dokument."
type: docs
weight: 1450
url: /sv/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Representerar alternativ för inläsning/import av SVG-fil i pdf-dokument.

Typen SvgLoadOptions visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| SvgLoadOptions() | Initierar en ny instans av klassen SvgLoadOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värde som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |
| load_format | Representerar filformat som [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beskriver. |
| page_info | Hämtar eller anger sidinformation som ska tillämpas under inläsning av dokumentet.<br/>            OBS att denna parameter endast fungerar när ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Justera pdf-sidans storlek till svg-storlek |
| conversion_engine | Tillåter att välja konverteringsmotor som kommer att användas under konverteringen.<br/>            Den nya motorn är för närvarande i B-testningsstadiet, så detta värde är som standard satt till <br/>            ConversionEngines.LegacyEngine |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

