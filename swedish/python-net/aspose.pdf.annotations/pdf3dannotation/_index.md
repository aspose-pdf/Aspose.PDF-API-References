---
title: "PDF3DAnnotation"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass PDF3DAnnotation. Denna klass kan inte ärvas."
type: docs
weight: 510
url: /sv/python-net/aspose.pdf.annotations/pdf3dannotation/
---

## PDF3DAnnotation class

Klass PDF3DAnnotation. Denna klass kan inte ärvas.

Typen PDF3DAnnotation exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PDF3DAnnotation(page, rect, pdf_3d_artwork) | Initierar en ny instans av klassen PDF3DAnnotation |
| PDF3DAnnotation(page, rect, pdf_3d_artwork, activation) | Initierar en ny instans av klassen PDF3DAnnotation |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| vertical_alignment | Hämtar eller anger en vertikal justering av stycket. |
| horizontal_alignment | Hämtar eller anger textjustering för annotationen. |
| margin | Hämtar eller anger en yttre marginal för stycket (för pdf‑generering) |
| is_first_paragraph_in_column | Hämtar eller anger ett bool‑värde som indikerar om detta stycke kommer att vara i nästa kolumn.<br/>            Standard är false.(för pdf‑generering) |
| is_kept_with_next | Hämtar eller anger ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke.<br/>            Standard är false.(för pdf‑generering) |
| is_in_new_page | Hämtar eller anger ett bool‑värde som tvingar detta stycke att genereras på en ny sida.<br/>            Standard är false.(för pdf‑generering) |
| is_in_line_paragraph | Hämtar eller anger om ett stycke är inline.<br/>            Standard är false.(för pdf‑generering) |
| hyperlänk | Hämtar eller anger fragment‑hyperlänken (för pdf‑generatorn). |
| z_index | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex <br/>            kommer att placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ <br/>            ZIndex kommer att placeras bakom texten på sidan. |
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
| pdf_3d_artwork | Hämtar 3D-konstverket. |
| lighting_scheme | Hämtar belysningsschemat. |
| content | Hämtar eller anger innehållet. |
| render_mode | Hämtar renderingsläget. |
| view_array | Hämtar vyarrayen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| set_image_preview(filename) | Ställer in bildförhandsgranskningen. |
| set_image_preview(image) | Ställer in bildförhandsgranskningen. |
| clone() | Klonar detta objekt.<br/>            Virtuell metod. Returnerar alltid null. |
| get_rectangle(consider_rotation) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| accept(visitor) | Accepterar besökare för annoteringsbearbetning. |
| flatten() | Placera annoteringsinnehåll direkt på sidan,<br/>            annoteringsobjektet kommer att tas bort. |
| change_after_resize(transform) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| set_default_view_index(index) | Ställer in indexet för standardvyn. |
| clear_image_preview() | Rensar bildförhandsgranskningen. |
| get_image_preview() | Hämtar bildförhandsgranskningen. |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

