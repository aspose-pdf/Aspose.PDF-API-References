---
title: "Class ImageDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.ImageDevice class. En abstrakt klass för bildenheter"
type: docs
weight: 3730
url: /sv/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

En abstrakt klass för bildenheter.

```csharp
public abstract class ImageDevice : PageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Abstrakt initierare för `ImageDevice`-avstammade, ställ in upplösning till 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Initierar en ny instans av klassen [`JpegDevice`](../jpegdevice/) med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Abstrakt initierare för `ImageDevice`-avstammade. Upplösning för den resulterande bildfilen, se klassen [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Initierar en ny instans av klassen [`JpegDevice`](../jpegdevice/) med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av klassen [`JpegDevice`](../jpegdevice/) med angivna bilddimensioner och upplösning. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av klassen [`JpegDevice`](../jpegdevice/) med angivna bilddimensioner och upplösning. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Utför någon operation på den angivna sidan, t.ex. konverterar sidan till en grafisk bild. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

### Se även

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


