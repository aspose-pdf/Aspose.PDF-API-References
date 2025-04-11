---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfPageStamp-Klasse. Klasse repräsentiert einen Stempel, der eine PDF-Seite als Stempel verwendet
type: docs
weight: 8420
url: /de/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp-Klasse

Klasse repräsentiert einen Stempel, der eine PDF-Seite als Stempel verwendet.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Seite) | Konstruktor von PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Erstellt einen PDF-Seitenstempel aus der angegebenen Seite im Dokument aus dem Stream. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Erstellt einen PDF-Seitenstempel aus der angegebenen Seite des Dokuments in der angegebenen Datei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Setzt oder erhält einen booleschen Wert, der angibt, dass der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten angeordnet. Standardmäßig ist der Wert false, der Stempelinhalt wird oben angeordnet. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Erhält oder setzt den unteren Rand des Stempels. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Gewünschte Höhe des Stempels auf der Seite. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Erhält oder setzt die horizontale Ausrichtung des Stempels auf der Seite. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Erhält oder setzt den linken Rand des Stempels. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Erhält oder setzt einen Wert, um die Opazität des Stempels anzuzeigen. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Erhält oder setzt einen Wert, um die Opazität des Stempelrandes anzuzeigen. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Erhält oder setzt einen Wert für die Breite des Stempelrandes. Standardmäßig ist der Wert 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Erhält oder setzt die Seite, die als Stempel verwendet wird. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Erhält oder setzt den rechten Rand des Stempels. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Setzt oder erhält die Rotation des Stempelinhalt gemäß den [`Rotation`](../rotation/) Werten. Hinweis: Diese Eigenschaft ist für Winkel, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die RotateAngle-Eigenschaft. Wenn der Winkel, der durch ArbitraryAngle festgelegt wird, kein Vielfaches von 90 ist, gibt die Rotate-Eigenschaft Rotation.None zurück. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Erhält oder setzt den Rotationswinkel des Stempels in Grad. Diese Eigenschaft ermöglicht es, einen beliebigen Rotationswinkel festzulegen. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Erhält oder setzt den oberen Rand des Stempels. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Erhält oder setzt die vertikale Ausrichtung des Stempels auf der Seite. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Gewünschte Breite des Stempels auf der Seite. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horizontale Stempelkoordinate, beginnend von links. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikale Stempelkoordinate, beginnend von unten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Zoom-Eigenschaft den Wert von ZoomX zurück. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horizontaler Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikaler Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Gibt die Stempel-ID zurück. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Seite) | Legt den Stempel auf der angegebenen Seite ab. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Setzt die Stempel-ID. |

### Siehe auch

* Klasse [Stamp](../stamp/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)