---
title: "PdfPageStamp"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen representerar en stämpel som använder en PDF-sida som stämpel."
type: docs
weight: 1230
url: /sv/python-net/aspose.pdf/pdfpagestamp/
---

## PdfPageStamp class

Klassen representerar en stämpel som använder en PDF-sida som stämpel.

Typen PdfPageStamp exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfPageStamp(pdf_page) | Initierar en ny instans av klassen PdfPageStamp |
| PdfPageStamp(file_name, page_index) | Initierar en ny instans av klassen PdfPageStamp |
| PdfPageStamp(stream, page_index) | Initierar en ny instans av klassen PdfPageStamp |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| bakgrund | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund.<br/>            Om värdet är true placeras stämpelinnehållet längst ner.<br/>            Som standard är värdet false, och stämpelinnehållet placeras högst upp. |
| opacitet | Hämtar eller anger ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0.<br/>            Som standard är värdet 1.0. |
| outline_opacity | Hämtar eller anger ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0.<br/>            Som standard är värdet 1.0. |
| outline_width | Hämtar eller anger ett värde för stämpelns konturbredd.<br/>            Som standard är värdet 1.0. |
| rotate | Ställer in eller hämtar rotationen för stämpelns innehåll enligt [Rotation](/pdf/python-net/aspose.pdf/rotation/) värden.<br/>            Obs. Denna egenskap är för vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader).<br/>            För att ange en godtycklig vinkel, använd egenskapen RotateAngle. <br/>            Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate‑egenskapen Rotation.None. |
| x_indent | Horisontell stämpelkoordinat, med början från vänster. |
| y_indent | Vertikal stämpelkoordinat, med början från botten. |
| horizontal_alignment | Hämtar eller anger horisontell justering av stämpeln på sidan. |
| vertical_alignment | Hämtar eller anger vertikal justering av stämpeln på sidan. |
| left_margin | Hämtar eller anger vänstermarginalen för stämpeln. |
| right_margin | Hämtar eller anger högermarginalen för stämpeln. |
| bottom_margin | Hämtar eller anger bottenmarginalen för stämpeln. |
| top_margin | Hämtar eller anger övre marginalen för stämpeln. |
| zoom_x | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| bredd | Önskad bredd på stämpeln på sidan. |
| höjd | Önskad höjd på stämpeln på sidan. |
| zoom_y | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |
| zoom | Zoomfaktor för stämpeln. Tillåter att skala stämpeln.<br/>            Observera att paret av egenskaper ZoomX och ZoomY tillåter att sätta zoomfaktor för varje axel separat. <br/>            Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. <br/>            Om ZoomX och ZoomY är olika returnerar Zoom-egenskapen ZoomX-värdet. |
| rotate_angle | Hämtar eller anger rotationsvinkeln för stämpeln i grader.<br/>            Denna egenskap tillåter att sätta en godtycklig rotationsvinkel. |
| pdf_page | Hämtar eller anger sidan som ska användas som stämpel. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| put(page) | Placera stämpeln på den angivna sidan. |
| set_stamp_id(value) | Anger stämpel‑ID. |
| get_stamp_id() | Returnerar stämpel‑ID. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

