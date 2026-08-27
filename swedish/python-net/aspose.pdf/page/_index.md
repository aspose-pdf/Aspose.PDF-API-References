---
title: "Page"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen som representerar en sida i PDF-dokumentet."
type: docs
weight: 1080
url: /sv/python-net/aspose.pdf/page/
---

## Page class

Klassen som representerar en sida i PDF-dokumentet.

Typen Page visar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_add_paragraphs_after_last | Hämtar eller anger tillägget av stycken efter det sista stycket på sidan |
| background_image | Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokumentet). |
| toc_info | Hämtar eller anger information om innehållsförteckning. |
| header | Hämtar eller anger sidhuvud. |
| layers | Hämtar eller anger lagerkollektion. |
| footer | Hämtar eller anger sidfot. |
| paragraphs | Hämtar styckena. |
| page_info | Hämtar eller anger sidinformation (endast för generator, fylls inte i vid läsning av dokument). |
| rektangel | Hämtar eller anger rektangeln för sidan.<br/>            Vid hämtning: sidans beskärningsruta returneras om den är specificerad, annars returneras sidans mediabox.<br/>            Vid inställning: mediaboxen för sidan sätts alltid.<br/>            Observera att den här egenskapen inte tar hänsyn till sidrotation. För att hämta sidrektangeln med hänsyn till rotation, använd ActualRect. |
| color_type | Anger färgtyp för sidorna baserat på information hämtad från operatorerna SetColor,<br/>            bilder och formulär. |
| note_line_style | Hämtar eller anger linjestilen för anteckningar (endast för generator, fylls inte i vid läsning av dokument). |
| tab_order | Hämtar eller anger flikordning för sidan. <br/>            Möjliga värden: Row, Column. Standard, Manual |
| duration | Hämtar eller anger sidans visningstid. Detta är tiden i sekunder som sidan ska visas under en presentation.<br/>            Returnerar -1 om varaktigheten inte är definierad. |
| contents | Hämtar samling av operatorer i sidans innehållsström.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| group | Hämtar eller anger en klass för gruppattribut som specificerar attributen för sidans sidgrupp för användning i den transparenta avbildningsmodellen. |
| annotations | Hämtar samling av sidanteckningar.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Hämtar sidresurser. Resursobjektet innehåller samlingar av bilder, formulär och teckensnitt.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| rotera | Hämtar eller anger rotationen för sidan. |
| trim_box | Hämtar eller anger trimrutan för sidan. |
| art_box | Hämtar eller anger art-rutan för sidan. |
| bleed_box | Hämtar eller anger bleed-rutan för sidan. |
| crop_box | Hämtar eller anger beskärningsrutan för sidan. |
| media_box | Hämtar eller anger media-rutan för sidan. |
| nummer | Hämta sidnumret. |
| rotation_matrix | Hämtar transformationsmatris för sidan. |
| bakgrund | Hämtar eller anger bakgrundsfärgen för sidan. |
| watermark | Hämtar eller anger vattenstämpeln för sidan. |
| artifacts | Hämtar samling av artefakter på sidan. |
| åtgärder | Hämtar samling av sidans egenskaper. |
| fields_in_tab_order | Hämtar lista över fältobjekt i tabb-ordning på den här sidan. |
| user_unit | Hämtar eller anger UserUnit‑värdet. Ett positivt tal som anger storleken på standard‑användarytenheter, i multiplar av 1 ⁄ 72 tum.<br/>            Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| send_to(device, output) | Skickar sidan för bearbetning med angiven sid-enhet. |
| send_to(device, output_file_name) | Skickar sidan för bearbetning med angiven sid-enhet. |
| accept(visitor) | Accepterar [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| accept(visitor) | Accepterar [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| accept(visitor) | Accepterar [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| accept(visitor) | Accepterar [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| add_image(image_stream, image_rect) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln och sparar bildens proportion. |
| add_image(hocr, image_stream, image_rect) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln och sparar bildens proportion. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Lägger till en bild på sidan och placerar den beroende på bildrektangelns position. |
| add_image(image_path, rectangle) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln och sparar bildens proportion. |
| is_blank(fill_threshold_factor) | Hämtar flaggan som anger om sidan är tom eller inte. |
| get_page_rect(consider_rotation) | Returnerar sidans rektangel enligt dess CropBox (eller MediaBox om CropBox är null). |
| calculate_content_b_box() | Beräknar bbox-värdet - rektangel som innehåller innehållet utan synliga marginaler. |
| rotation_to_int(rotation) | Översätter rotationsenum-medlem till ett heltalsvärde. |
| int_to_rotation(rotation) | Översätter heltalsvärdet till motsvarande rotationsenum-medlem. |
| add_stamp(stamp) | Placera stämpel på sidan. Stämpeln kan vara sidnummer, bild eller enkel text, t.ex. en logotyp. |
| flatten() | Tar bort alla fält som finns på sidan och placerar deras värden istället. |
| set_page_size(width, height) | Ställer in sidstorlek för sidan. |
| make_grayscale() | Konverterar sidan till gråskala. |
| free_memory() | Rensar cachad data. |
| get_notifications() | Returnerar aviseringar om interna operationer med sidinnehåll. (Endast aviseringar om paragraf-händelser i scenarier för texttillägg stöds för närvarande.) |
| as_byte_array(resolution) | Konverterar aktuell sida till bitmap och returnerar sedan en byte-array. |
| as_xml() | Konverterar aktuell sida till xml i utf8-kodning. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

