---
title: ThumbnailDevice
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt ein Bildgerät dar das Seiten von PDF-Dokumenten als Miniaturbild speichert.
type: docs
weight: 1790
url: /de/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Stellt ein Bildgerät dar, das Seiten von PDF-Dokumenten als Miniaturbild speichert.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice#constructor)() | Initialisiert eine neue Instanz von[`ThumbnailDevice`](../thumbnaildevice) class mit Standardgröße des Thumbnail-Bildes (200 x 200 Pixel). |
| [ThumbnailDevice](thumbnaildevice#constructor_1)(int, int) | Initialisiert eine neue Instanz von[`ThumbnailDevice`](../thumbnaildevice) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Holt oder setzt den Seitenkoordinatentyp (Media/Crop-Boxen). CropBox-Wert wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Ruft den Präsentationsmodus des Formulars ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Ruft die Bildausgabehöhe ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Ruft Wiedergabeoptionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Ruft die Bildausgabebreite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process#process)(Page, Stream) | Konvertiert die Seite in ein Miniaturbild im PNG-Format und speichert es im Ausgabestream. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Führt einige Operationen auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

### Siehe auch

* class [ImageDevice](../imagedevice)
* namensraum [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->