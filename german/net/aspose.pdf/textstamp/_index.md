---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TextStamp-Klasse. Stellt einen textuellen Stempel dar
type: docs
weight: 11080
url: /de/net/aspose.pdf/textstamp/
---
## TextStamp-Klasse

Stellt einen textuellen Stempel dar.

```csharp
public class TextStamp : Stamp
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | Initialisiert eine neue Instanz der `TextStamp`-Klasse mit einem FormatiertenText-Objekt |
| [TextStamp](textstamp/#constructor_1)(string) | Initialisiert eine neue Instanz der `TextStamp`-Klasse. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | Initialisiert eine neue Instanz der `TextStamp`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Passt die Schriftgröße automatisch an. Standardwert: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Wenn aktiviert, wird die Schriftgröße automatisch angepasst, um in das Stempelrechteck der Größe: [`Width`](./width/) und [`Height`](./height/) zu passen. Standardbreite und -höhe stammen aus dem Seitenrechteck. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Setzt oder erhält einen booleschen Wert, der angibt, dass der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten platziert. Standardmäßig ist der Wert false, der Stempelinhalt wird oben platziert. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Erhält oder setzt den unteren Rand des Stempels. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Wenn Draw = true, wird der Stempel als grafische Operatoren gezeichnet, und wenn Draw = false, wird der Stempel als Text gezeichnet. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Tatsächliche Schriftgröße, nachdem der Stempel platziert wurde. (Kann von der ursprünglichen Schriftgröße abweichen, die über den Konstruktor bereitgestellt wurde, wenn die Option 'AutoAdjustFontSizeToFitStampRectangle' aktiviert ist.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Gewünschte Höhe des Stempels auf der Seite. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Erhält oder setzt die horizontale Ausrichtung des Stempels auf der Seite. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Definiert die Textausrichtung. Wenn diese Eigenschaft auf true gesetzt ist, sind sowohl die linke als auch die rechte Kante des Textes ausgerichtet. Standardwert: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Erhält oder setzt den linken Rand des Stempels. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Maximale Zeilenhöhe für die WordWrap-Option. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Erhält oder setzt den Modus, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Erhält oder setzt einen Wert, um die Opazität des Stempels anzuzeigen. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Erhält oder setzt einen Wert, um die Opazität der Stempelkontur anzuzeigen. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Erhält oder setzt einen Wert für die Breite der Stempelkontur. Standardmäßig ist der Wert 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Erhält oder setzt die Schriftart, die zum Ersetzen verwendet wird, wenn die Benutzer-Schriftart das erforderliche Zeichen nicht enthält. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Erhält oder setzt den rechten Rand des Stempels. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Setzt oder erhält die Drehung des Stempelinhalt gemäß den [`Rotation`](../rotation/) Werten. Hinweis. Diese Eigenschaft ist für die Festlegung von Winkeln, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die RotateAngle-Eigenschaft. Wenn der Winkel, der durch ArbitraryAngle festgelegt wird, kein Vielfaches von 90 ist, gibt die Rotate-Eigenschaft Rotation.None zurück. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Erhält oder setzt den Drehwinkel des Stempels in Grad. Diese Eigenschaft ermöglicht es, einen beliebigen Drehwinkel festzulegen. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf true gesetzt ist und ein Wert für die Breite angegeben ist, wird der Text skaliert, um in die angegebene Breite zu passen. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Ausrichtung des Textes innerhalb des Stempels. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Erhält die Texteigenschaften des Stempels. Siehe [`TextState`](./textstate/) für Details. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Erhält oder setzt den oberen Rand des Stempels. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Definiert den Koordinatenursprung für die Platzierung des Textes. Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true) wird der YIndent-Wert als Textbasislinie behandelt. Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false) wird der YIndent-Wert als untere (Abstiegslinie) des Textes behandelt. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Erhält oder setzt den Stringwert, der als Stempel auf der Seite verwendet wird. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Erhält oder setzt die vertikale Ausrichtung des Stempels auf der Seite. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Gewünschte Breite des Stempels auf der Seite. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Erhält oder setzt den Zeilenumbruchmodus für die Textdarstellung. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horizontale Stempelkoordinate, beginnend von links. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikale Stempelkoordinate, beginnend von unten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Zoom-Eigenschaft den Wert von ZoomX zurück. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horizontaler Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikaler Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Gibt die Stempel-ID zurück. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | Fügt einen textuellen Stempel auf der Seite hinzu. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Setzt die Stempel-ID. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | Aktion, die ausgeführt werden soll, wenn die Schriftart das erforderliche Zeichen nicht enthält. |

### Siehe auch

* Klasse [Stamp](../stamp/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)