---
title: "LineAnnotation"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar line‑annotation."
type: docs
weight: 380
url: /sv/python-net/aspose.pdf.annotations/lineannotation/
---

## LineAnnotation class

Klass som representerar line‑annotation.

Typen LineAnnotation exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| LineAnnotation(document, start, end) | Initierar en ny instans av klassen LineAnnotation |
| LineAnnotation(page, rect, start, end) | Initierar en ny instans av klassen LineAnnotation |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| vertical_alignment | Ingen |
| horizontal_alignment | Hämtar eller anger textjustering för annotationen. |
| margin | Ingen |
| is_first_paragraph_in_column | Ingen |
| is_kept_with_next | Ingen |
| is_in_new_page | Ingen |
| is_in_line_paragraph | Ingen |
| hyperlänk | Ingen |
| z_index | Ingen |
| uppdatera_utseende_vid_konvertering | Om true, uppdateras annoteringens utseende innan PF-dokumentet konverteras till bild. Detta möjliggör korrekt konvertering av fält men kan kräva mer tid. |
| använd_teckensnitt_delmängd | Om den här egenskapen är satt till true, kommer typsnitt att läggas till dokumentet som delmängder. Standardvärdet är true. |
| flaggor | Flaggor för annoteringen. |
| annoteringstyp | Hämtar typ av annotering. |
| bredd | Hämtar eller anger bredden på annoteringen. |
| åtgärder | Hämtar lista över annoteringsåtgärder. |
| höjd | Hämtar eller anger höjden på annoteringen. |
| rektangel | Hämtar eller anger annoteringsrektangel. |
| innehåll | Hämtar eller anger annoteringstexten. |
| name | Hämtar eller anger annoteringsnamnet på sidan. |
| modifierad | Hämtar eller anger datum och tid då annoteringen senast ändrades. |
| färg | Hämtar eller anger annoteringsfärgen. |
| border | Hämtar eller anger annoteringens kantegenskaper. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| aktivt_tillstånd | Hämtar eller anger aktuellt annoteringsutseende. |
| karaktäristika | Hämtar annoteringens egenskaper. |
| tillstånd | Hämtar utseendedictionary för annoteringen. |
| justering | Anotationsjustering. Denna egenskap är föråldrad. Använd HorizontalAligment istället. |
| text_horisontell_justering | Hämtar eller anger textjustering för annotationen. |
| fullständigt_namn | Hämtar det fullständigt kvalificerade namnet på annoteringen. |
| utseende | Hämtar utseendedictionary för annoteringen. |
| sidindex | Hämtar sidans index som innehåller annoteringen. |
| titel | Hämtar eller anger en text som ska visas i titelraden för annoteringen. |
| rich_text | Hämtar eller anger en rik textsträng som ska visas i popup-fönstret när annoteringen öppnas. |
| creation_date | Hämtar datum och tid då annoteringen skapades. |
| subject | Hämtar text som representerar beskrivning av objektet. |
| popup | Popup-annotering för att ange eller redigera texten som är kopplad till denna annotering. |
| opacitet | Hämtar eller anger det konstanta opacitetsvärdet som ska användas vid målning av annoteringen. |
| in_reply_to | En referens till annoteringen som denna annotering är "i svar på".<br/>            Båda annoteringarna måste vara på samma sida i dokumentet. |
| reply_type | En sträng som specificerar relationen ("svarstypen") mellan denna annotering<br/>            och den som anges av InReplyTo. |
| starting | Hämtar eller anger startpunkt för linjen. |
| starting_style | Hämtar eller anger linjens slutstil för startpunkten. |
| ending | Hämtar eller anger linjens slutpunkt. |
| ending_style | Hämtar eller anger slutstil för linjens slutpunkt. |
| interior_color | Hämtar eller anger den inre färgen på annoteringen. |
| leader_line | Hämtar eller anger ledarlinjens längd. |
| leader_line_extension | Hämtar eller anger längden på ledarlinjeutökningen. |
| show_caption | Hämtar eller anger en boolesk flagga som bestämmer om innehållet ska visas som rubrik. |
| leader_line_offset | Hämtar eller anger ledarlinjens offset. |
| caption_offset | Hämtar eller anger förskjutning av bildtextens text från dess normala position. |
| caption_position | Hämtar eller anger annoteringens bildtextposition. |
| mått | Måttenheter specificerade för denna annotation. |
| avsikt | Hämtar eller anger avsikten med radannoteringen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Ingen |
| get_rectangle(consider_rotation) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| accept(visitor) | Accepterar besökare för annoteringsbearbetning. |
| flatten() | Placera annoteringsinnehåll direkt på sidan,<br/>            annoteringsobjektet kommer att tas bort. |
| change_after_resize(transform) | Uppdaterar start- och slutpunkterna enligt matrisomvandlingen. |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

