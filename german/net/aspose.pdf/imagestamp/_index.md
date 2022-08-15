---
title: ImageStamp
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert den grafischen Stempel.
type: docs
weight: 3790
url: /de/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Repräsentiert den grafischen Stempel.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageStamp](imagestamp#constructor)(Stream) | Initialisiert eine neue Instanz von[`ImageStamp`](../imagestamp) Klasse. |
| [ImageStamp](imagestamp#constructor_1)(string) | Erstellt Bildstempel nach Bild in der angegebenen Datei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Setzt oder erhält einen Bool-Wert, der anzeigt, dass der Inhalt als Hintergrund gestempelt wird. Wenn der Wert wahr ist, wird der Stempelinhalt nach unten gelegt. Standardmäßig ist der Wert falsch, der Stempelinhalt wird nach oben gelegt. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Ruft den unteren Rand des Stempels ab oder legt ihn fest. |
| [Height](../../aspose.pdf/imagestamp/height) { get; set; } | Ermittelt oder setzt die Bildhöhe. Wenn Sie dieses Bild einstellen, können Sie das Bild vertikal skalieren. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Holt oder setzt die horizontale Ausrichtung des Stempels auf der Seite. |
| [Image](../../aspose.pdf/imagestamp/image) { get; } | Ruft den zum Stempeln verwendeten Bildstrom ab. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Ruft den linken Rand des Stempels ab oder legt ihn fest. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, um die Deckkraft der Stempelkontur anzugeben. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Liest oder setzt einen Wert der Umrissbreite des Stempels. Standardmäßig ist der Wert 1,0. |
| [Quality](../../aspose.pdf/imagestamp/quality) { get; set; } | Ermittelt oder setzt die Qualität des Bildstempels in Prozent. Gültige Werte sind 0..100 %. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Ruft den rechten Rand des Stempels ab oder legt ihn fest. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Setzt oder erhält die Drehung des Stempelinhalts entsprechend[`Rotation`](../rotation) Werte. Hinweis. Diese Eigenschaft dient zum Festlegen von Winkeln, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die Eigenschaft RotateAngle. Wenn der von ArbitraryAngle festgelegte Winkel kein Vielfaches von 90 ist, gibt die Rotate-Eigenschaft Rotation.None. zurück. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Ermittelt oder setzt den Rotationswinkel des Stempels in Grad. Diese Eigenschaft erlaubt es, einen beliebigen Rotationswinkel einzustellen. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Ruft den oberen Rand des Stempels ab oder legt ihn fest. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Ruft die vertikale Ausrichtung des Stempels auf der Seite ab oder legt sie fest. |
| [Width](../../aspose.pdf/imagestamp/width) { get; set; } | Ermittelt oder setzt die Bildbreite. Wenn Sie diese Eigenschaft festlegen, wird das Bild horizontal skaliert. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Horizontale Stempelkoordinate, von links beginnend. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Vertikale Stempelkoordinate, von unten beginnend. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Zoomfaktor des Stempels. Ermöglicht das Skalieren von Stempeln. Bitte beachten Sie, dass das Eigenschaftspaar ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat einzustellen. Die Einstellung dieser Eigenschaft ändert sowohl die ZoomX- als auch die ZoomY-Eigenschaft. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Zoom-Eigenschaft den ZoomX-Wert zurück. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Horizontaler Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Vertikaler Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Rücksendestempel ID. |
| override [Put](../../aspose.pdf/imagestamp/put)(Page) | Fügt einen Grafikstempel auf der Seite hinzu. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Setzt die Stempel-ID. |

### Siehe auch

* class [Stamp](../stamp)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
