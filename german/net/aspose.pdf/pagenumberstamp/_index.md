---
title: PageNumberStamp
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt den Seitenzahlstempel dar und wird zum Nummerieren von Seiten verwendet.
type: docs
weight: 5890
url: /de/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Stellt den Seitenzahlstempel dar und wird zum Nummerieren von Seiten verwendet.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PageNumberStamp](pagenumberstamp#constructor)() | Initialisiert eine neue Instanz von[`PageNumberStamp`](../pagenumberstamp) Klasse. Format ist auf "#". gesetzt |
| [PageNumberStamp](pagenumberstamp#constructor_1)(FormattedText) | Erstellt PageNumberStamp durch formatierten Text. |
| [PageNumberStamp](pagenumberstamp#constructor_2)(string) | Initialisiert eine neue Instanz von[`PageNumberStamp`](../pagenumberstamp) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Setzt oder erhält einen Bool-Wert, der anzeigt, dass der Inhalt als Hintergrund gestempelt wird. Wenn der Wert wahr ist, wird der Stempelinhalt nach unten gelegt. Standardmäßig ist der Wert falsch, der Stempelinhalt wird nach oben gelegt. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Ruft den unteren Rand des Stempels ab oder legt ihn fest. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Bei Draw = true wird stamp als Grafikoperator gezeichnet und bei draw = false wird stamp als Text gezeichnet. |
| [Format](../../aspose.pdf/pagenumberstamp/format) { get; set; } | Zeichenfolgenwert zum Stempeln von Seitenzahlen. Der Wert muss das Zeichen „#“ enthalten, das beim Stempeln durch die Seitenzahl ersetzt wird. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Gewünschte Höhe des Stempels auf der Seite. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Holt oder setzt die horizontale Ausrichtung des Stempels auf der Seite. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Definiert die Textausrichtung. Wenn diese Eigenschaft auf „true“ gesetzt ist, werden sowohl der linke als auch der rechte Rand des Textes ausgerichtet. Standardwert: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Ruft den linken Rand des Stempels ab oder legt ihn fest. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Maximale Zeilenhöhe für WordWrap-Option. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle) { get; set; } | Nummerierungsstil, der von diesem Stempel verwendet wird. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, um die Deckkraft der Stempelkontur anzugeben. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Liest oder setzt einen Wert der Umrissbreite des Stempels. Standardmäßig ist der Wert 1,0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Ruft den rechten Rand des Stempels ab oder legt ihn fest. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Setzt oder erhält die Drehung des Stempelinhalts entsprechend[`Rotation`](../rotation) Werte. Hinweis. Diese Eigenschaft dient zum Festlegen von Winkeln, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die Eigenschaft RotateAngle. Wenn der von ArbitraryAngle festgelegte Winkel kein Vielfaches von 90 ist, gibt die Rotate-Eigenschaft Rotation.None. zurück. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Ermittelt oder setzt den Rotationswinkel des Stempels in Grad. Diese Eigenschaft erlaubt es, einen beliebigen Rotationswinkel einzustellen. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf „true“ gesetzt und der Wert „Breite“ angegeben ist, wird der Text so skaliert, dass er auf die angegebene Breite passt. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber) { get; set; } | Erhält oder setzt den Wert der Nummer der Startseite. Andere Seiten werden ab diesem Wert nummeriert. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Ausrichtung des Textes innerhalb des Stempels. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Ruft Texteigenschaften des Stempels ab. Sehen[`TextState`](../textstamp/textstate) für Details. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Ruft den oberen Rand des Stempels ab oder legt ihn fest. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Definiert den Koordinatenursprung zum Platzieren von Text. Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true ist), wird der YIndent-Wert als Grundlinie des Textes behandelt. Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false) wird der YIndent-Wert als untere ( Abstiegslinie) von text. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Erhält oder setzt einen String-Wert, der als Stempel auf der Seite verwendet wird. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Ruft die vertikale Ausrichtung des Stempels auf der Seite ab oder legt sie fest. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Gewünschte Breite des Stempels auf der Seite. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Definiert Zeilenumbruch. Wenn diese Eigenschaft auf „true“ gesetzt und der Wert „Breite“ angegeben ist, wird der Text in mehreren Zeilen umbrochen, um in die angegebene Breite zu passen. Standardwert: false. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Horizontale Stempelkoordinate, von links beginnend. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Vertikale Stempelkoordinate, von unten beginnend. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Zoomfaktor des Stempels. Ermöglicht das Skalieren von Stempeln. Bitte beachten Sie, dass das Eigenschaftspaar ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat einzustellen. Die Einstellung dieser Eigenschaft ändert sowohl die ZoomX- als auch die ZoomY-Eigenschaft. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Zoom-Eigenschaft den ZoomX-Wert zurück. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Horizontaler Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Vertikaler Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Rücksendestempel ID. |
| override [Put](../../aspose.pdf/pagenumberstamp/put)(Page) | Fügt Seitenzahl hinzu. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Setzt die Stempel-ID. |

### Siehe auch

* class [TextStamp](../textstamp)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
