---
title: "BarcodeField"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen representerar ett streckkodfält."
type: docs
weight: 10
url: /sv/python-net/aspose.pdf.forms/barcodefield/
---

## BarcodeField class

Klassen representerar ett streckkodfält.

Typen BarcodeField exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| BarcodeField(page, rect) | Initierar en ny instans av klassen BarcodeField |
| BarcodeField(doc, rect) | Initierar en ny instans av klassen BarcodeField |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| vertical_alignment | Ingen |
| horizontal_alignment | Ingen |
| margin | Ingen |
| is_first_paragraph_in_column | Ingen |
| is_kept_with_next | Ingen |
| is_in_new_page | Ingen |
| is_in_line_paragraph | Ingen |
| hyperlänk | Ingen |
| z_index | Ingen |
| uppdatera_utseende_vid_konvertering | Ingen |
| använd_teckensnitt_delmängd | Ingen |
| flaggor | Ingen |
| annoteringstyp | Ingen |
| bredd | Ingen |
| åtgärder | Ingen |
| höjd | Ingen |
| rektangel | Hämtar eller anger fältrektangeln. |
| innehåll | Ingen |
| name | Ingen |
| modifierad | Ingen |
| färg | Ingen |
| kant | Ingen |
| aktivt_tillstånd | Ingen |
| karaktäristika | Ingen |
| tillstånd | Ingen |
| justering | Ingen |
| text_horisontell_justering | Ingen |
| fullständigt_namn | Ingen |
| utseende | Ingen |
| sidindex | Hämtar sidindex för sidan som innehåller detta fält. |
| vid_aktivering | Ingen |
| markering | Ingen |
| förälder | Ingen |
| default_appearance | Ingen |
| read_only | Ingen |
| required | Ingen |
| exportable | Ingen |
| partial_name | Hämtar eller anger delnamn för fältet. |
| alternate_name | Hämtar eller anger alternativt namn för fältet (Ett alternativt fält <br/> namn som ska användas i stället för det faktiska fältnamnet <br/> där fältet ska identifieras i användargränssnittet).<br/> Alternativt namn används som verktygstips för fältet i Adobe Acrobat. |
| mapping_name | Hämtar eller anger mappningsnamn för fältet som ska användas vid export av interaktiva formulärfältsdata från dokumentet. |
| value | Hämtar eller anger värde för fältet. |
| is_synchronized | Returnerar true om ordboken är synkroniserad. |
| sync_root | Synkroniseringsobjekt. |
| is_group | Hämtar eller anger ett booleskt värde som indikerar om detta fält är ett icke‑terminalt fält, d.v.s. en grupp av fält. |
| annotation_index | Hämtar eller anger index för denna annotation på sidan. |
| is_shared_field | Egenskap för Generator‑stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende kommer att vara synligt på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida. |
| fit_into_rectangle | Om true minskas teckenstorleken för att passa texten i den angivna rektangeln. |
| max_font_size | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| min_font_size | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| tab_order | Hämtar eller anger tabbordning för fältet. |
| multiline | Hämtar eller anger flerradig flagga för fältet. Om Multiline är true kan fältet innehålla flera rader text. |
| spell_check | Hämtar eller anger stavningskontrollflagga för fältet. Om true ska fältet stavningskontrolleras. |
| scrollable | Hämtar eller anger rullningsbar flagga för fältet. Om true kan fältet rullas. |
| force_combs | Hämtar eller anger flagga som indikerar om fältet är delat i separata positioner. |
| max_len | Hämtar eller anger maximal längd för text i fältet. |
| text_vertical_alignment | Hämtar eller anger vertikal textjustering för annotation. |
| resolution | Hämtar upplösningen, i punkter per tum (dpi), som streckkodobjektet renderas med. |
| caption | Hämtar rubriken för streckkodobjektet. |
| symbology | Anger vilken streckkod- eller glyfteknik som ska användas på denna annotation,<br/>            se [symbology](/pdf/python-net/aspose.pdf.forms/barcodefield/) för detaljer. |
| x_sym_width | Hämtar det horisontella avståndet, i pixlar, mellan två streckkodmoduler. |
| x_sym_height | Hämtar det vertikala avståndet mellan två streckkodmoduler, mätt i pixlar. <br/>            Förhållandet XSymHeight/XSymWidth ska vara ett heltal. <br/>            För PDF417 är det accepterade förhållandet mellan 1 och 4. För QRCode och DataMatrix ska detta förhållande alltid vara 1 |
| ecc | Hämtar ett heltalsvärde som representerar felkorrigeringskoefficienten. <br/>            För PDF417 ska det vara mellan 0 och 8. För QRCode ska det vara mellan 0 och 3 <br/>            (0 för �L�, 1 för �M�, 2 för �Q�, och 3 för �H�). |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar underfält som finns i detta fält enligt index. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Ingen |
| get_rectangle(consider_rotation) | Ingen |
| accept(visitor) | Ingen |
| flatten() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| change_after_resize(transform) | Ingen |
| recalculate() | Beräknar om alla beräknade fält i formuläret. |
| copy_to(array, index) | Kopierar underfält från detta fält till arrayen med start från angivet index. |
| set_position(point) | Ställ in fältets position. |
| add_image(image) | Lägger till en bild i fältets resurser och ritar den. |
| add_barcode(code) | Lägger till streckkod 128 i fältet. <br/>            Fältvärdet kommer att ändras till koden och fältet blir skrivskyddat. |

### Se även

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

