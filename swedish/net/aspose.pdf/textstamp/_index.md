---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TextStamp klass. Representerar textstämplar
type: docs
weight: 11080
url: /sv/net/aspose.pdf/textstamp/
---
## TextStamp klass

Representerar textstämplar.

```csharp
public class TextStamp : Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | Initierar en ny instans av `TextStamp` klassen med formattedText objekt |
| [TextStamp](textstamp/#constructor_1)(string) | Initierar en ny instans av `TextStamp` klassen. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | Initierar en ny instans av `TextStamp` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Justera automatiskt teckenstorlekens precision. Standardvärde: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Om aktiverad kommer teckenstorleken automatiskt att justeras för att passa stämpelrektangeln med storlek: [`Width`](./width/) och [`Height`](./height/). Standardbredd och -höjd härleds från sidrektangeln. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Sätter eller hämtar ett bool-värde som indikerar att innehållet stämplas som bakgrund. Om värdet är sant, läggs stämpelinnehållet längst ner. Som standard är värdet falskt, stämpelinnehållet läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller sätter bottenmarginalen för stämpeln. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om draw = false ritas stämpeln som text. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Faktisk teckenstorlek efter att stämpeln har placerats. (Kan skilja sig från den initiala teckenstorleken som tillhandahålls genom konstruktorn om alternativet 'AutoAdjustFontSizeToFitStampRectangle' är aktiverat.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Önskad höjd på stämpeln på sidan. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller sätter horisontell justering av stämpeln på sidan. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Definierar textjustering. Om denna egenskap är inställd på true, justeras både vänster och höger kant av texten. Standardvärde: falskt. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller sätter vänster marginal för stämpeln. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Max radbredd för WordWrap-alternativet. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Hämtar eller sätter läget som definierar beteendet om typsnitt inte innehåller begärda tecken. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller sätter ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller sätter ett värde för att indikera stämpelns konturens opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller sätter ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Hämtar eller sätter typsnitt som används för att ersätta om användartypsnittet inte innehåller det erforderliga tecknet. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller sätter höger marginal för stämpeln. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Sätter eller hämtar rotationen av stämpelinnehållet enligt [`Rotation`](../rotation/) värden. Obs. Denna egenskap är för att ställa in vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ställa in en godtycklig vinkel, använd RotateAngle-egenskapen. Om vinkeln som ställs in av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller sätter rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ställa in en godtycklig rotationsvinkel. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Definierar skalning av texten. Om denna egenskap är inställd på true och breddvärdet anges, kommer texten att skalas för att passa den angivna bredden. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Justering av texten inuti stämpeln. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Hämtar textens egenskaper för stämpeln. Se [`TextState`](./textstate/) för detaljer. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller sätter överkantens marginal för stämpeln. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Definierar koordinatorigin för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent-värdet att behandlas som textens baslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent-värdet att behandlas som botten (nedgångslinje) av texten. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Hämtar eller sätter strängvärdet som används som stämpel på sidan. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller sätter vertikal justering av stämpeln på sidan. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Önskad bredd på stämpeln på sidan. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Hämtar eller sätter ordomslagsläget för textåtergivning. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horisontell stämpelkoordinat, som börjar från vänster. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikal stämpelkoordinat, som börjar från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Möjliggör skalning av stämpeln. Observera att paret av egenskaper ZoomX och ZoomY möjliggör att ställa in zoomfaktorn för varje axel separat. Inställning av denna egenskap ändrar både ZoomX och ZoomY egenskaper. Om ZoomX och ZoomY är olika returnerar Zoom-egenskapen ZoomX-värdet. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Möjliggör skalning av stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Möjliggör skalning av stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpel-ID. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | Lägger till textstämplar på sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Sätter stämpel-ID. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | Åtgärd att utföra om typsnittet inte innehåller det erforderliga tecknet. |

### Se även

* klass [Stamp](../stamp/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)