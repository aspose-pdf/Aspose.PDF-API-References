---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ThumbnailDevice-Klasse. Stellt ein Bildgerät dar, das Seiten von PDF-Dokumenten in Thumbnail-Bilder speichert.
type: docs
weight: 3690
url: /de/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice-Klasse

Stellt ein Bildgerät dar, das Seiten von PDF-Dokumenten in Thumbnail-Bilder speichert.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Initialisiert eine neue Instanz der `ThumbnailDevice`-Klasse mit der Standardgröße des Thumbnail-Bildes (200x200 Pixel). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Initialisiert eine neue Instanz der `ThumbnailDevice`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Höhe des Bildausgangs ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Breite des Bildausgangs ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Konvertiert die Seite in ein Thumbnail-Bild im PNG-Format und speichert es im Ausgabestream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine bestimmte Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

### Siehe auch

* Klasse [ImageDevice](../imagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)