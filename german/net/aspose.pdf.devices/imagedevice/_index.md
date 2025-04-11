---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice-Klasse. Eine abstrakte Klasse für Bildgeräte
type: docs
weight: 3610
url: /de/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice-Klasse

Eine abstrakte Klasse für Bildgeräte.

```csharp
public abstract class ImageDevice : PageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Abstrakter Initialisierer für `ImageDevice`-Nachkommen, setzt die Auflösung auf 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Initialisiert eine neue Instanz der [`JpegDevice`](../jpegdevice/) Klasse mit den angegebenen Bildabmessungen und der Standardauflösung (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Abstrakter Initialisierer für `ImageDevice`-Nachkommen. Auflösung für die resultierende Bilddatei, siehe [`Resolution`](./resolution/) Klasse. |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Initialisiert eine neue Instanz der [`JpegDevice`](../jpegdevice/) Klasse mit den angegebenen Bildabmessungen und der Standardauflösung (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Initialisiert eine neue Instanz der [`JpegDevice`](../jpegdevice/) Klasse mit den angegebenen Bildabmessungen und der Auflösung. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Initialisiert eine neue Instanz der [`JpegDevice`](../jpegdevice/) Klasse mit den angegebenen Bildabmessungen und der Auflösung. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Höhe der Bildausgabe ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Breite der Bildausgabe ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Führt eine Operation auf der angegebenen Seite aus, z.B. konvertiert die Seite in ein grafisches Bild. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

### Siehe auch

* Klasse [PageDevice](../pagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)