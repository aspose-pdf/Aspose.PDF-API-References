---
title: "XpsSaveOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Spara alternativ för export till Xps-format"
type: docs
weight: 1810
url: /sv/python-net/aspose.pdf/xpssaveoptions/
---

## XpsSaveOptions class

Spara alternativ för export till Xps-format

Typen XpsSaveOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| XpsSaveOptions() | Initierar en ny instans av klassen XpsSaveOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och spara‑operationen fortsätter, men användaren kan också returnera Abort, varvid spara‑operationen ska avbrytas. |
| save_format | Format för datasparning. |
| close_response | Hämtar eller anger ett booleskt värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| extract_ocr_sublayer_only | Detta attribut aktiverar funktionalitet för att extrahera bild eller text <br/>            för PDF-dokument med OCR sublayer. |
| try_merge_adjacent_same_background_images | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller)<br/>              konstruerade av flera identiska mosaikbakgrundsbilder placerade bredvid varandra.<br/>              I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera<br/>              synliga gränser mellan delar av bakgrundsbilderna,<br/>              eftersom deras teknik för kantutjämning (anti-aliasing) skiljer sig från Acrobat Reader.<br/>               Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan <br/>              delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av <br/>              med den oönskade effekten. <br/>                ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt,<br/>              så vänligen använd detta alternativ endast när det verkligen är nödvändigt. |
| save_transparent_texts | Anger om transparent (OCR:ad) text ska bevaras. |
| batch_size | Definierar batch‑storlek om batch‑konvertering är tillämplig<br/>            för käll‑ och målformatpar. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

