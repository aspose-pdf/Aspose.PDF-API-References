---
title: "RedactionAnnotation"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar raderings‑annotation."
type: docs
weight: 680
url: /sv/python-net/aspose.pdf.annotations/redactionannotation/
---

## RedactionAnnotation class

Representerar raderings‑annotation.

Typen RedactionAnnotation exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| RedactionAnnotation(document) | Initierar en ny instans av klassen RedactionAnnotation |
| RedactionAnnotation(page, rect) | Initierar en ny instans av klassen RedactionAnnotation |
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
| quad_point | En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort. |
| default_appearance | Hämtar eller anger standardutseendesträngen som ska användas vid formatering av texten. |
| fill_color | Hämtar eller anger färg för att fylla annotationen. |
| border_color | Hämtar eller anger färg på kantlinjen som ritas när redigering inte är aktiv. |
| overlay_text | Text att skriva ut på raderingsanteckning. |
| upprepa | Om true kommer overlay text att upprepas på anteckningen. |
| text_alignment | Hämtar eller anger. Justering av overlay text. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Ingen |
| get_rectangle(consider_rotation) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| accept(visitor) | Accepterar besöksobjekt för att bearbeta annoteringen. |
| flatten() | Plattar till annotation, d.v.s. tar bort annotation och lägger till dess |
| change_after_resize(transform) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| redact() | Plattar till annotation och raderar sidinnehåll (d.v.s. tar bort text och bild under raderad annotation) |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

