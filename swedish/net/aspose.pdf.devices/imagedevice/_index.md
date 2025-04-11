---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice klass. En abstrakt klass för bildenheter
type: docs
weight: 3610
url: /sv/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice klass

En abstrakt klass för bildenheter.

```csharp
public abstract class ImageDevice : PageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Abstrakt initialiserare för `ImageDevice`-avkommor, sätter upplösning till 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Abstrakt initialiserare för `ImageDevice`-avkommor. Upplösning för den resulterande bildfilen, se [`Resolution`](./resolution/) klass. |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angivna bilddimensioner och upplösning. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angivna bilddimensioner och upplösning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller sätter sidkoordinattyp (Media/Crop-boxar). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utgångshöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller sätter renderingalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utgångsbred. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Utför en operation på den angivna sidan, t.ex. konverterar sidan till en grafisk bild. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

### Se Även

* klass [PageDevice](../pagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)