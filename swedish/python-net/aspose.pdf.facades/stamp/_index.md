---
title: "Stamp"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar en stämpel."
type: docs
weight: 410
url: /sv/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Klass som representerar en stämpel.

Typen Stamp visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Stamp() | Initierar en ny instans av klassen Stamp |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| stamp_id | Hämtar eller anger identifierare för stämpeln. |
| kvalitet | Hämtar eller anger kvalitet för bildstämpel i procent. Giltiga värden 0..100%. |
| opacitet | Hämtar eller anger opacitet för stämpeln. |
| page_number | Hämtar eller anger sidnummer. |
| sidor | Hämtar eller anger en array med sidnummer som kommer att påverkas av stämpeln. <br/>            Om Pages = null påverkas alla sidor i dokumentet. |
| rotation | Hämtar eller anger rotation för stämpeln i grader. |
| is_background | Hämtar eller anger bakgrundsstatus. Om true placeras stämpeln som bakgrund på den stämplade sidan.<br/>            Som standard är den satt till false. |
| blending_space | Hämtar eller anger ett BlendingColorSpace‑värde som definierar ett färgrymd <br/>            som används för att utföra transparens‑ och blandningsoperationer på sidan. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Anger PDF‑fil och sidnummer som kommer att användas som stämpel. |
| bind_pdf(pdf_stream, page_number) | Anger PDF‑fil och sidnummer som kommer att användas som stämpel. |
| bind_image(image_file) | Anger bild som en stämpel. |
| bind_image(image) | Anger bild som kommer att användas som stämpel. |
| bind_logo(formatted_text) | Anger text som stämpel. |
| bind_text_state(text_state) | Anger texttillstånd för stämpelns text. |
| set_origin(origin_x, origin_y) | Ställer in position på sidan där stämpeln kommer att placeras. |
| set_image_size(width, height) | Ställer in storlek på bildstämpeln. Bilden kommer att skalas enligt de angivna värdena. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

