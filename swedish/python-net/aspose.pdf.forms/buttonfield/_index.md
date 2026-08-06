---
title: "ButtonField"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen representerar ett tryckknappfält."
type: docs
weight: 20
url: /sv/python-net/aspose.pdf.forms/buttonfield/
---

## ButtonField class

Klassen representerar ett tryckknappfält.

ButtonField-typen visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| ButtonField() | Konstruktör för knappfält för Generator. |
| ButtonField(page, rect) | Initierar en ny instans av klassen ButtonField |
| ButtonField(doc, rect) | Initierar en ny instans av klassen ButtonField |
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
| annoteringstyp | Hämtar typ av annotering. |
| bredd | Ingen |
| åtgärder | Hämtar annoteringsåtgärderna. |
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
| vid_aktivering | En åtgärd som ska utföras när annoteringen aktiveras. |
| markering | Annoteringsmarkeringsläge. |
| förälder | Hämtar annoteringens förälder. |
| default_appearance | Hämtar eller anger standardutseende för fältet. |
| read_only | Hämtar eller anger skrivskyddad status för fältet. |
| required | Hämtar eller anger obligatorisk status för fältet. |
| exportable | Hämtar eller anger exportflagga för fältet. |
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
| normal_caption | Hämtar eller anger normal rubrik. |
| rollover_caption | Hämtar eller anger rullningsrubrik för knappen som ska visas när användaren rullar markören <br/>            in i dess aktiva område utan att trycka på musknappen. |
| alternate_caption | Hämtar eller anger alternativ rubrik för knappen som ska visas <br/>            när musknappen trycks ned inom dess aktiva område. |
| normal_icon | Hämtar eller anger normal ikon för knappen som ska visas när den inte interagerar med användaren. |
| rollover_icon | Hämtar eller anger rullningsikon för knappen som ska visas när användaren <br/>            rullar markören in i dess aktiva område utan att trycka på musknappen. |
| alternate_icon | Hämtar eller anger alternativ ikon som ska visas när musknappen trycks ned inom dess aktiva område. |
| icon_fit | Hämtar ikonpassningsobjekt som specificerar hur widget-annotationens ikon ska visas inom dess annoteringsrektangel. |
| ic_position | Hämtar eller anger ikonrubrikens position. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar underfält som finns i detta fält enligt index. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Ingen |
| get_rectangle(consider_rotation) | Ingen |
| accept(visitor) | Accepterar besökare. |
| flatten() | Tar bort detta fält och placerar dess värde direkt på sidan. |
| change_after_resize(transform) | Ingen |
| recalculate() | Beräknar om alla beräknade fält i formuläret. |
| copy_to(array, index) | Kopierar underfält från detta fält till arrayen med start från angivet index. |
| set_position(point) | Ställ in fältets position. |
| add_image(image) | Lägger till en bild i fältets resurser och ritar den. |

### Se även

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

