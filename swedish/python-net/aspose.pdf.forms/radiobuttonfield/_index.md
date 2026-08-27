---
title: "RadioButtonField"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar radioknappsfält."
type: docs
weight: 220
url: /sv/python-net/aspose.pdf.forms/radiobuttonfield/
---

## RadioButtonField class

Klass som representerar radioknappsfält.

Typen RadioButtonField exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| RadioButtonField(page) | Initierar en ny instans av klassen RadioButtonField |
| RadioButtonField(doc) | Initierar en ny instans av klassen RadioButtonField |
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
| sidindex | Hämtar sidindex för den sida som innehåller detta RadioButton-fält. |
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
| value | Hämtar eller anger fältets värde. |
| is_synchronized | Returnerar true om ordboken är synkroniserad. |
| sync_root | Synkroniseringsobjekt. |
| is_group | Hämtar eller anger ett booleskt värde som indikerar om detta fält är ett icke‑terminalt fält, d.v.s. en grupp av fält. |
| annotation_index | Hämtar eller anger index för denna annotation på sidan. |
| is_shared_field | Egenskap för Generator‑stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende kommer att vara synligt på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida. |
| fit_into_rectangle | Om true minskas teckenstorleken för att passa texten i den angivna rektangeln. |
| max_font_size | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| min_font_size | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| tab_order | Hämtar eller anger tabbordning för fältet. |
| commit_immediately | Hämtar eller anger flaggan för omedelbar commit vid urvalsförändring. |
| multi_select | Hämtar eller anger flaggan för multival. |
| selected | Hämtar eller anger index för valt objekt. Numrering av objekt startar från 1. |
| selected_items | Hämtar eller anger en array av valda objekt. För flervalslista innehåller arrayen mer än ett objekt. För enkellista innehåller den ett enda objekt. |
| alternativ | Hämtar samling av alternativ för radioknappen. |
| style | Stil för fältboxen. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar underfält som finns i detta fält enligt index. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| add_option(option_name, rect) | Lägg till  till radioknappsalternativ med specificerad rektangel. |
| add_option(option_name) | Lägg till  till radioknappsalternativ med specificerad rektangel. |
| add_option(export, name) | Lägg till  till radioknappsalternativ med specificerad rektangel. |
| clone() | Ingen |
| get_rectangle(consider_rotation) | Ingen |
| accept(visitor) | Ingen |
| flatten() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| change_after_resize(transform) | Ingen |
| recalculate() | Beräknar om alla beräknade fält i formuläret. |
| copy_to(array, index) | Kopierar underfält från detta fält till arrayen med start från angivet index. |
| set_position(point) | Flytta alla underobjekt för radioknappen till angivna positioner på sidan. |
| delete_option(option_name) | Tar bort alternativet efter dess namn. |
| add(new_item) | Lägger till ett nytt alternativfält till RadioButton-fältet. |

### Se även

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

