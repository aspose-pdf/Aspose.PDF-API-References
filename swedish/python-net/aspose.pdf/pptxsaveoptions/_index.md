---
title: "PptxSaveOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Spara alternativ för export till SVG-format"
type: docs
weight: 1290
url: /sv/python-net/aspose.pdf/pptxsaveoptions/
---

## PptxSaveOptions class

Spara alternativ för export till SVG-format

Typen PptxSaveOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PptxSaveOptions() | Initierar en ny instans av klassen PptxSaveOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och spara‑operationen fortsätter, men användaren kan också returnera Abort, varvid spara‑operationen ska avbrytas. |
| save_format | Format för datasparning. |
| close_response | Hämtar eller anger ett booleskt värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| extract_ocr_sublayer_only | Detta attribut aktiverar funktionalitet för att extrahera bild eller text <br/>            för PDF-dokument med OCR sublayer. |
| try_merge_adjacent_same_background_images | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller)<br/>              konstruerade av flera identiska mosaikbakgrundsbilder placerade bredvid varandra.<br/>              I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera<br/>              synliga gränser mellan delar av bakgrundsbilderna,<br/>              eftersom deras teknik för kantutjämning (anti-aliasing) skiljer sig från Acrobat Reader.<br/>               Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan <br/>              delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av <br/>              med den oönskade effekten. <br/>                ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt,<br/>              så vänligen använd detta alternativ endast när det verkligen är nödvändigt. |
| slides_as_images | Om den är satt till true så känns allt innehåll igen som bilder (en per sida) |
| image_resolution | Hämtar eller anger bildens upplösning (dpi). Standard är 192 dpi. |
| separate_images | Om den är satt till true separeras bilder från all annan grafik |
| optimize_text_boxes | Växlar igenkänning av textkolumner |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

