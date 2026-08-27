---
title: "RichMediaAnnotation"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljuddata i PDF-dokumentet."
type: docs
weight: 710
url: /sv/python-net/aspose.pdf.annotations/richmediaannotation/
---

## RichMediaAnnotation class

Klass som beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljuddata i PDF-dokumentet.

Typen RichMediaAnnotation exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| RichMediaAnnotation(page, rect) | Initierar en ny instans av klassen RichMediaAnnotation |
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
| custom_player | Ställer in eller hämtar anpassad flash‑spelare för att spela video-/ljuddata. |
| custom_flash_variables | Ställer in eller hämtar flash‑variabler som skickas till spelaren. |
| content | Data för Rich Media‑innehållet. |
| type | Hämtar eller ställer in typ av innehåll. Möjliga värden: Audio, Video. |
| activate_on | Händelse som aktiverar applikationen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Klonar detta objekt.<br/>            Virtuell metod. Returnerar alltid null. |
| get_rectangle(consider_rotation) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| accept(visitor) | Accepterar besökare för denna annotation. |
| flatten() | Placera annoteringsinnehåll direkt på sidan,<br/>            annoteringsobjektet kommer att tas bort. |
| change_after_resize(transform) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| add_custom_data(name, data) | Lägg till anpassad namngiven data (till exempel krävs för flash‑script). |
| set_content(file_name, audio) | Ställ in innehållsström. |
| set_poster(image_stream) | Ställ in postern för annoteringen. |
| update() | Uppdaterar data med angivna parametrar. |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

