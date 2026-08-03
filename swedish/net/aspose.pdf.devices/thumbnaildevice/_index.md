---
title: "Klass ThumbnailDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.ThumbnailDevice-klass. Representerar en bildenhet som sparar pdf-dokumentets sidor som en Thumbnail-bild"
type: docs
weight: 3810
url: /sv/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Representerar bildenhet som sparar PDF-dokumentets sidor som miniatyrbild.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Initierar en ny instans av klassen `ThumbnailDevice` med standardstorlek för thumbnail-bilden (200x200 pixlar). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Initierar en ny instans av klassen `ThumbnailDevice`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller anger formulärets presentationsläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller anger renderingsalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Konverterar sidan till Bitmap. |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Konverterar sidan till thumbnail-bilden png och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

### Se även

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


