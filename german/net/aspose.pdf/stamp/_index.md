---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Stamp-Klasse. Eine abstrakte Klasse für verschiedene Arten von Stempeln, die als Nachkommen kommen
type: docs
weight: 10130
url: /de/net/aspose.pdf/stamp/
---
## Stamp-Klasse

Eine abstrakte Klasse für verschiedene Arten von Stempeln, die als Nachkommen kommen.

```csharp
public abstract class Stamp
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Legt einen booleschen Wert fest oder ruft ihn ab, der angibt, dass der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten angeordnet. Standardmäßig ist der Wert false, der Stempelinhalt wird oben angeordnet. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ruft den unteren Rand des Stempels ab oder legt ihn fest. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Gewünschte Höhe des Stempels auf der Seite. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Stempels auf der Seite ab oder legt sie fest. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ruft den linken Rand des Stempels ab oder legt ihn fest. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, um die Opazität des Stempels anzugeben. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, um die Opazität des Stempelumrisses anzugeben. Der Wert liegt zwischen 0.0 und 1.0. Standardmäßig ist der Wert 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ruft einen Wert für die Breite des Stempelumrisses ab oder legt ihn fest. Standardmäßig ist der Wert 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ruft den rechten Rand des Stempels ab oder legt ihn fest. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Legt die Rotation des Stempelinhalts gemäß den [`Rotation`](../rotation/) Werten fest oder ruft sie ab. Hinweis: Diese Eigenschaft ist für Winkel, die Vielfache von 90 Grad (0, 90, 180, 270 Grad) sind. Um einen beliebigen Winkel festzulegen, verwenden Sie die RotateAngle-Eigenschaft. Wenn der Winkel, der durch ArbitraryAngle festgelegt wird, kein Vielfaches von 90 ist, gibt die Rotate-Eigenschaft Rotation.None zurück. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ruft den Rotationswinkel des Stempels in Grad ab oder legt ihn fest. Diese Eigenschaft ermöglicht es, einen beliebigen Rotationswinkel festzulegen. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ruft den oberen Rand des Stempels ab oder legt ihn fest. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Stempels auf der Seite ab oder legt sie fest. |
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
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Fügt den Stempel auf der Seite hinzu. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Legt die Stempel-ID fest. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)