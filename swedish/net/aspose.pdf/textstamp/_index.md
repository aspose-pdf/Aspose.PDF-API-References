---
title: TextStamp
second_title: Aspose.PDF för .NET API Referens
description: Återanger textstämpel.
type: docs
weight: 7240
url: /sv/net/aspose.pdf/textstamp/
---
## TextStamp class

Återanger textstämpel.

```csharp
public class TextStamp : Stamp
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextStamp](textstamp#constructor)(FormattedText) | Initierar en ny instans av[`TextStamp`](../textstamp) klass med formattedText object |
| [TextStamp](textstamp#constructor_1)(string) | Initierar en ny instans av[`TextStamp`](../textstamp) class. |
| [TextStamp](textstamp#constructor_2)(string, TextState) | Initierar en ny instans av[`TextStamp`](../textstamp) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Ställer in eller får ett boolvärde som indikerar att innehållet är stämplat som bakgrund. Om värdet är sant, läggs stämpelinnehållet längst ner. Av defalt är värdet falskt, stämpelinnehållet läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Får eller ställer in bottenmarginalen på stämpeln. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Den här egenskapen bestämmer hur stämpeln ritas på sidan. Om Draw = true stämpel ritas som grafiska operatorer och om draw = false så ritas stämpeln som text. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Önskad höjd på stämpeln på sidan. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Hämtar eller ställer in horisontell justering av stämpeln på sidan. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Definierar textjustering. Om den här egenskapen är inställd på true, justeras både vänster och höger kanter av texten. Standardvärde: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Hämtar eller ställer in vänster marginal på stämpeln. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Max radhöjd för WordWrap-alternativ. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Hämtar eller ställer in ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Hämtar eller ställer in ett värde för att indikera stämpelkonturens opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Hämtar eller ställer in ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Får eller ställer in höger marginal på stämpeln. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Ställer in eller hämtar rotationen av stämpelinnehåll enligt[`Rotation`](../rotation) värden. Obs. Den här egenskapen är för inställda vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). Använd RotateAngle-egenskapen för att ställa in godtycklig vinkel. Om vinkeln inställd av ArbitraryAngle inte är multipel av 90 returnerar Rotate-egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Hämtar eller ställer in stämpelns rotationsvinkel i grader. Den här egenskapen gör det möjligt att ställa in godtycklig rotationsvinkel. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Definierar skalningen av texten. Om den här egenskapen är inställd på true och Width-värdet anges, skalas texten för att passa till specificerad width. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Justering av texten inuti stämpeln. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Hämtar textegenskaper för stämpeln. Ser[`TextState`](./textstate) för detaljer. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Får eller ställer in den övre marginalen på stämpeln. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Definierar koordinatursprung för att placera text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) YIndent-värde kommer att behandlas som textbasrad. Om TreatYIndentAsBaseLine = false (standardvärde när Draw = true) kommer YIndent-värdet att behandlas som textbaslinje. Om TreatYIndentAsBaseLine = false (standardvärde när Draw = true) nedstigningslinje) av text. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Hämtar eller ställer in strängvärde som används som stämpel på sidan. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Får eller ställer in vertikal justering av stämpeln på sidan. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Önskad bredd på stämpeln på sidan. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Definierar radbrytning. Om den här egenskapen är inställd på true och Width-värdet anges, kommer texten att brytas på flera rader för att passa in i angiven bredd. Standardvärde: false. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Horisontell stämpelkoordinat, med början från vänster. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Vertikal stämpelkoordinat, från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Zoomningsfaktor för stämpeln. Tillåter att skala stämpel. Observera att par av egenskaper ZoomX och ZoomY tillåter att ställa in zoomfaktor för varje yxa separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaper. Om ZoomX och ZoomY är olika returnerar Zoom-egenskapen ZoomX-värdet. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Stämpelns horisontella zoomfaktor. Tillåter att skala stämpel horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpel vertikalt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Returnerar stämpel-ID. |
| override [Put](../../aspose.pdf/textstamp/put)(Page) | Lägger till textstämpel på sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Anger stämpel-ID. |

### Se även

* class [Stamp](../stamp)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
