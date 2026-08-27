---
title: "Klass FloatingBox"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.FloatingBox‑klass."
type: docs
weight: 4990
url: /sv/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Initierar en ny instans av klassen `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Initierar en ny instans av klassen `FloatingBox` med angiven bredd och höjd. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Hämtar eller anger ett [`Color`](../color/)‑objekt som indikerar bakgrundsfärgen för den flytande rutan. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Hämtar eller anger bakgrundsbild för sidan (endast för generator, inte ifylld vid läsning av dokument). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Hämtar eller anger ett [`BorderInfo`](../borderinfo/)‑objekt som indikerar kantinformationen för den flytande rutan. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Hämtar eller anger kolumninformation |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Hämtar eller anger ett flyttal som indikerar höjden på den flytande rutan. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av stycket. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om stycket ska upprepas på nästa sida. Standardvärdet är false. Attributet är endast giltigt när själva stycket och det objekt som dess ReferenceParagraphID refererar till båda ingår i RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Hämtar eller anger tabellens vänstra koordinat. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Hämtar eller anger ett [`MarginInfo`](../margininfo/)‑objekt som indikerar utfyllnaden för den flytande rutan. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Hämtar eller anger en [`Paragraphs`](./paragraphs/)‑samling som indikerar alla stycken i cellen. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Anger variant för att bestämma placeringen av FloatingBox på sidan. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Hämtar eller anger tabellens övre koordinat. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Hämtar eller anger ett flyttal som indikerar bredden på den flytande rutan. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Klonar ett nytt `FloatingBox`‑objekt. Stycken i den flytande rutan klonas inte. |

### Se även

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


