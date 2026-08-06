---
title: "FooterArtifact"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Beskriver sidfotselement. Detta kan användas för att sätta sidfot på sidan."
type: docs
weight: 400
url: /sv/python-net/aspose.pdf/footerartifact/
---

## FooterArtifact class

Beskriver sidfotselement. Detta kan användas för att sätta sidfot på sidan.

Typen FooterArtifact exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| FooterArtifact() | Skapar en Footer Artifact-instans. |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| custom_type | Hämtar namn på artefakttyp. Kan användas om artefakttypen är icke‑standard. |
| custom_subtype | Hämtar namn på artefaktens undertyp. Kan användas om artefaktens undertyp inte är standard. |
| type | Hämtar artefakttyp. |
| subtype | Hämtar artefaktens undertyp. Om artefakten har en icke‑standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| innehåll | Hämtar samling av artefaktens interna operatörer. |
| formulär | Hämtar XForm för artefakten (om XForm används). |
| rectangle | Hämtar rektangel för artefakten. |
| position | Hämtar eller anger artefaktens position.<br/>            Om denna egenskap är specificerad ignoreras marginaler och justeringar. |
| right_margin | Höger marginal för artefakt. <br/>            Om position specificeras explicit (i egenskapen Position) ignoreras detta värde. |
| left_margin | Vänster marginal för artefakt. <br/>            Om position specificeras explicit (i egenskapen Position) ignoreras detta värde. |
| top_margin | Övre marginal för artefakt. <br/>            Om position specificeras explicit (i egenskapen Position) ignoreras detta värde. |
| bottom_margin | Nedre marginal för artefakt. <br/>            Om position specificeras explicit (i egenskapen Position) ignoreras detta värde. |
| artifact_horizontal_alignment | Horisontell justering av artefakt. <br/>            Om position specificeras explicit (i egenskapen Position) ignoreras detta värde. |
| artifact_vertical_alignment | Vertikal justering av artefakt. <br/>            Om position specificeras explicit (i egenskapen Position) ignoreras detta värde. |
| rotation | Hämtar eller anger rotationsvinkel för artefakt. |
| text | Hämtar texten för artefakten. |
| image | Hämtar bild av artefakten (om den finns). |
| opacitet | Hämtar eller anger opacitet för artefakten. Möjliga värden är i intervallet 0..1. |
| lines | Rader i flerradig textartefakt. |
| text_state | Textstatus för artefaktens text. |
| is_background | Om true placeras artefakten bakom sidans innehåll. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| set_image(image_stream) | Anger bild för artefakten. |
| set_image(image_name) | Anger bild för artefakten. |
| set_text(formatted_text) | Anger text för artefakten. |
| set_text_and_state(text, text_state) | Ställ in text och textegenskaper för artefakten. |
| set_lines_and_state(text, text_state) | Ställ in text och textegenskaper för artefakten. Tillåter att ange flera rader. |
| set_pdf_page(page) | Anger PDF-sida som placeras på dokumentsidan som artefakt. |
| get_value(name) | Hämtar anpassat värde för artefakten. |
| set_value(name, value) | Anger anpassat värde för artefakten. |
| remove_value(name) | Tar bort anpassat värde från artefakten. |
| begin_updates() | Starta fördröjda uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. <br/>            Vanligtvis ändras artefaktoperatorer när som helst när en artefakt‑egenskap ändras. Detta orsakar att sidinnehållet ändras<br/>            varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan StartUpdates/SaveUpdates‑anrop.<br/>            Detta möjliggör att sidinnehållet bara ändras en gång. |
| save_updates() | Sparar alla uppdateringar i artefakten som gjordes efter anropet BeginUpdates(). |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

