---
title: "Klass PageNumberStamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PageNumberStamp-klass. Representerar sidnumreringsstämpel och används för att numrera sidor"
type: docs
weight: 8370
url: /sv/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Representerar en sidnummerstämpel som används för att numrera sidor.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Initierar en ny instans av klassen `PageNumberStamp`. Formatet är satt till "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Skapar PageNumberStamp med formaterad text. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Initierar en ny instans av klassen `PageNumberStamp`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Om aktiverat kommer teckenstorleken automatiskt att justeras för att passa stämpelrektangeln med storleken: [`Width`](../textstamp/width/) och [`Height`](../textstamp/height/). Standardbredd och -höjd hämtas från sidrektangeln. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true läggs stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller anger nedre marginal för stämpeln. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om draw = false ritas stämpeln som text. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Faktisk teckenstorlek efter att stämpeln har placerats. (Kan skilja sig från den ursprungliga teckenstorleken som angavs via konstruktorn om alternativet 'AutoAdjustFontSizeToFitStampRectangle' är aktiverat.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Strängvärde för att stämpla sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Önskad höjd på stämpeln på sidan. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller anger horisontell justering av stämpeln på sidan. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Definierar textjustering. Om denna egenskap är satt till true justeras både vänster- och högerranden av texten. Standardvärde: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller anger vänster marginal för stämpeln. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Maximal radhöjd för WordWrap-alternativet. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Hämtar eller anger läget som definierar beteendet om teckensnitt inte innehåller de begärda tecknen. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Numreringsstil som används av denna stämpel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller anger ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller anger ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller anger ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller anger högermarginalen för stämpeln. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Ställer in eller hämtar rotationen av stämpelns innehåll enligt [`Rotation`](../rotation/) värden. Obs! Denna egenskap är för att ange vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90 så returnerar Rotate‑egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller anger rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Definierar skalning av texten. Om denna egenskap är satt till true och ett Width‑värde har angetts, kommer texten att skalas för att passa den angivna bredden. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Hämtar eller anger värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Justering av texten inom stämpeln. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Hämtar textegenskaper för stämpeln. Se [`TextState`](../textstamp/textstate/) för detaljer. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller anger övre marginalen för stämpeln. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textbaslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) för texten. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Hämtar eller anger strängvärdet som används som stämpel på sidan. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering av stämpeln på sidan. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Önskad bredd på stämpeln på sidan. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Hämtar eller anger ordbrytningsläget för textrendering. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horisontell stämpelkoordinat, räknat från vänster. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikal stämpelkoordinat, räknat från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika returnerar Zoom‑egenskapen ZoomX‑värdet. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpelns ID. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Lägger till sidnummer. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Anger stämpelns ID. |

### Se även

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


