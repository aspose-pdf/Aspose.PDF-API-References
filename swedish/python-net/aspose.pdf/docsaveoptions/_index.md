---
title: "DocSaveOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Spara alternativ för export till Doc-format"
type: docs
weight: 220
url: /sv/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Spara alternativ för export till Doc-format

DocSaveOptions-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| DocSaveOptions() | Initierar en ny instans av DocSaveOptions-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och spara‑operationen fortsätter, men användaren kan också returnera Abort, varvid spara‑operationen ska avbrytas. |
| save_format | Format för datasparning. |
| close_response | Hämtar eller anger ett booleskt värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| extract_ocr_sublayer_only | Detta attribut aktiverar funktionalitet för att extrahera bild eller text <br/>            för PDF-dokument med OCR sublayer. |
| try_merge_adjacent_same_background_images | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller)<br/>              konstruerade av flera identiska mosaikbakgrundsbilder placerade bredvid varandra.<br/>              I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera<br/>              synliga gränser mellan delar av bakgrundsbilderna,<br/>              eftersom deras teknik för kantutjämning (anti-aliasing) skiljer sig från Acrobat Reader.<br/>               Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan <br/>              delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av <br/>              med den oönskade effekten. <br/>                ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt,<br/>              så vänligen använd detta alternativ endast när det verkligen är nödvändigt. |
| mode | igenkänningsläge |
| relative_horizontal_proximity | I PDF kan ord internt representeras med operatorer som skriver ut ord<br/>              genom att oberoende skriva ut deras bokstäver eller stavelser. Så för att upptäcka ord måste vi ibland identifiera grupper<br/>              av oberoende tecken som faktiskt är ord.<br/>                Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) <br/>              som ska behandlas som avstånd mellan ord under igenkänning av ord i käll‑PDF.<br/>              (närvaro av ett tomt utrymme åtminstone med denna bredd mellan bokstäver betyder att <br/>               textelementen tillhör olika ord).<br/>              Den är normaliserad till teckenstorlek – 1.0 betyder 100 % av det förväntade ordets teckenstorlek.<br/>             OBS! Den används endast i fall då käll‑PDF innehåller specifika sällan använda teckensnitt<br/>             för vilka det optimala värdet inte kan beräknas från teckensnittet. <br/>               Så i de allra flesta fall förändrar denna parameter inget i resultatdokumentet. |
| max_distance_between_text_lines | Denna parameter används för att gruppera textrader i stycken.<br/>            Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av textradernas höjd. |
| recognize_bullets | Aktivera igenkänning av punktlistor |
| add_return_to_line_end | Använd stycke- eller radbrytningar |
| image_resolution_x | Konverterade bilders X-upplösning. |
| image_resolution_y | Konverterade bilders Y-upplösning. |
| format | Utdataformat |
| batch_size | Definierar batch‑storlek om batch‑konvertering är tillämplig<br/>            för käll‑ och målformatpar. |
| memory_save_mode_path | Definierar sökvägen (filnamn eller katalognamn) för att lagra<br/>            temporära data vid konvertering i minnessparläge. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

