---
title: "LaTeXSaveOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Spara alternativ för export till TeX-format."
type: docs
weight: 800
url: /sv/python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

Spara alternativ för export till TeX-format.

Typen LaTeXSaveOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| LaTeXSaveOptions() | Initierar en ny instans av klassen LaTeXSaveOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Ingen |
| save_format | Ingen |
| close_response | Ingen |
| extract_ocr_sublayer_only | Detta attribut aktiverar funktionalitet för att extrahera bild eller text <br/>            för PDF-dokument med OCR sublayer. |
| try_merge_adjacent_same_background_images | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller)<br/>              konstruerade av flera identiska mosaikbakgrundsbilder placerade bredvid varandra.<br/>              I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera<br/>              synliga gränser mellan delar av bakgrundsbilderna,<br/>              eftersom deras teknik för kantutjämning (anti-aliasing) skiljer sig från Acrobat Reader.<br/>               Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan <br/>              delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av <br/>              med den oönskade effekten. <br/>                ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt,<br/>              så vänligen använd detta alternativ endast när det verkligen är nödvändigt. |
| out_directory_path | Egenskap för |
| pages_count | Returnerar antalet sidor efter konvertering. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| add_font_encs(font_encs) | Lägger till en teckensnittskodning i teckensnittskodningslistan |
| clear_font_encs() | Rensar teckensnittskodningslistan |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

