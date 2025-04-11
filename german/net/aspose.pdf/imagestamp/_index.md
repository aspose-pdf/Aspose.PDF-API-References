---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp-Klasse. Stellt einen grafischen Stempel dar
type: docs
weight: 5930
url: /de/net/aspose.pdf/imagestamp/
---
## ImageStamp-Klasse

Stellt einen grafischen Stempel dar.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Initialisiert eine neue Instanz der `ImageStamp`-Klasse. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Erstellt einen Bildstempel aus dem Bild in der angegebenen Datei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Ruft den alternativen Text für den Bildstempel ab oder legt ihn fest. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Legt einen booleschen Wert fest, der angibt, dass der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten angeordnet. Standardmäßig ist der Wert false, der Stempelinhalt wird oben angeordnet. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ruft den unteren Rand des Stempels ab oder legt ihn fest. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Ruft die Bildhöhe ab oder legt sie fest. Das Festlegen dieses Bildes ermöglicht das vertikale Skalieren des Bildes. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Stempels auf der Seite ab oder legt sie fest. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Ruft den Bildstream ab, der für das Stempeln verwendet wird. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ruft den linken Rand des Stempels ab oder legt ihn fest. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, um die Opazität des Stempels anzugeben. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, um die Opazität der Stempelumrandung anzugeben. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ruft einen Wert für die Breite der Stempelumrandung ab oder legt ihn fest. Standardmäßig ist der Wert 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Ruft die Qualität des Bildstempels in Prozent ab oder legt sie fest. Gültige Werte sind 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ruft den rechten Rand des Stempels ab oder legt ihn fest. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Legt die Drehung des Stempelinhalt gemäß den [`Rotation`](../rotation/) Werten fest oder ruft sie ab. Hinweis: Diese Eigenschaft ist für Winkel, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die RotateAngle-Eigenschaft. Wenn der Winkel, der durch ArbitraryAngle festgelegt wird, kein Vielfaches von 90 ist, gibt die Rotate-Eigenschaft Rotation.None zurück. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ruft den Drehwinkel des Stempels in Grad ab oder legt ihn fest. Diese Eigenschaft ermöglicht das Festlegen eines beliebigen Drehwinkels. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ruft den oberen Rand des Stempels ab oder legt ihn fest. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Stempels auf der Seite ab oder legt sie fest. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Ruft die Bildbreite ab oder legt sie fest. Das Festlegen dieser Eigenschaft ermöglicht das horizontale Skalieren des Bildes. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Ruft die horizontale Stempelkoordinate ab und legt sie fest, beginnend von links. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Ruft die vertikale Stempelkoordinate ab und legt sie fest, beginnend von unten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Festlegen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Zoom-Eigenschaft den Wert von ZoomX zurück. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horizontaler Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikaler Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Gibt die Stempel-ID zurück. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Fügt einen grafischen Stempel auf der Seite hinzu. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Legt die Stempel-ID fest. |

### Siehe auch

* Klasse [Stamp](../stamp/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)