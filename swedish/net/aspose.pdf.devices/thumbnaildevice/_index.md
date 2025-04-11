---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ThumbnailDevice klass. Representerar en bildanordning som sparar pdf-dokument sidor i Thumbnail-bild
type: docs
weight: 3690
url: /sv/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice klass

Representerar en bildanordning som sparar pdf-dokument sidor i Thumbnail-bild.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Initierar en ny instans av `ThumbnailDevice` klassen med standardstorlek för thumbnail-bild (200x200 pixlar). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Initierar en ny instans av `ThumbnailDevice` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller sätter sidkoordinattyp (Media/Crop-boxar). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller sätter renderingalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Konverterar sidan till thumbnail-bild png och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

### Se Även

* klass [ImageDevice](../imagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)