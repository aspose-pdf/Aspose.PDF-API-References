---
title: "TextStamp"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar textuell stämpel."
type: docs
weight: 1550
url: /sv/python-net/aspose.pdf/textstamp/
---

## TextStamp class

Representerar textuell stämpel.

Typen TextStamp exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TextStamp(value) | Initierar en ny instans av klassen TextStamp |
| TextStamp(value, text_state) | Initierar en ny instans av klassen TextStamp |
| TextStamp(formatted_text) | Initierar en ny instans av klassen TextStamp |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| bakgrund | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund.<br/>            Om värdet är true placeras stämpelinnehållet längst ner.<br/>            Som standard är värdet false, och stämpelinnehållet placeras högst upp. |
| opacitet | Hämtar eller anger ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0.<br/>            Som standard är värdet 1.0. |
| outline_opacity | Hämtar eller anger ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0.<br/>            Som standard är värdet 1.0. |
| outline_width | Hämtar eller anger ett värde för stämpelns konturbredd.<br/>            Som standard är värdet 1.0. |
| rotate | Ställer in eller hämtar rotationen för stämpelns innehåll enligt [Rotation](/pdf/python-net/aspose.pdf/rotation/) värden.<br/>            Obs. Denna egenskap är för vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader).<br/>            För att ange en godtycklig vinkel, använd egenskapen RotateAngle. <br/>            Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate‑egenskapen Rotation.None. |
| x_indent | Horisontell stämpelkoordinat, med början från vänster. |
| y_indent | Vertikal stämpelkoordinat, med början från botten. |
| horizontal_alignment | Hämtar eller anger horisontell justering av stämpeln på sidan. |
| vertical_alignment | Hämtar eller anger vertikal justering av stämpeln på sidan. |
| left_margin | Hämtar eller anger vänstermarginalen för stämpeln. |
| right_margin | Hämtar eller anger högermarginalen för stämpeln. |
| bottom_margin | Hämtar eller anger bottenmarginalen för stämpeln. |
| top_margin | Hämtar eller anger övre marginalen för stämpeln. |
| zoom_x | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| bredd | Önskad bredd på stämpeln på sidan. |
| höjd | Önskad höjd på stämpeln på sidan. |
| zoom_y | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |
| zoom | Zoomfaktor för stämpeln. Tillåter att skala stämpeln.<br/>            Observera att paret av egenskaper ZoomX och ZoomY tillåter att sätta zoomfaktor för varje axel separat. <br/>            Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. <br/>            Om ZoomX och ZoomY är olika returnerar Zoom-egenskapen ZoomX-värdet. |
| rotate_angle | Hämtar eller anger rotationsvinkeln för stämpeln i grader.<br/>            Denna egenskap tillåter att sätta en godtycklig rotationsvinkel. |
| draw | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om Draw = false ritas stämpeln som text. |
| treat_y_indent_as_base_line | Definierar koordinatursprung för placering av text.<br/>            Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent-värdet att behandlas som textbaslinje.<br/>            Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent-värdet att behandlas som botten (nedstigningslinje) av text. |
| word_wrap | Definierar radbrytning. Om den här egenskapen är satt till true och Width‑värdet anges, kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false. |
| justify | Definierar textjustering. Om den här egenskapen är satt till true, aligneras både vänstra och högra kanterna på texten. Standardvärde: false. |
| skala | Definierar skalning av texten. Om den här egenskapen är satt till true och Width‑värdet anges, kommer texten att skalas för att passa den angivna bredden. |
| value | Hämtar eller anger strängvärdet som används som stämpel på sidan. |
| text_state | Hämtar textegenskaperna för stämpeln. Se [text_state](/pdf/python-net/aspose.pdf/textstamp/) för detaljer. |
| text_alignment | Justering av texten inuti stämpeln. |
| max_row_width | Maximal radhöjd för WordWrap‑alternativet. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| put(page) | Lägger till en textstämpel på sidan. |
| set_stamp_id(value) | Anger stämpel‑ID. |
| get_stamp_id() | Returnerar stämpel‑ID. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

