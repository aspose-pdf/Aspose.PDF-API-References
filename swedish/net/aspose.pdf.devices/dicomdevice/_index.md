---
title: "Klass DicomDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.DicomDevice-klass. Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor i Dicom-format."
type: docs
weight: 3680
url: /sv/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

Representerar en bildenhet som hjälper till att spara pdf‑dokumentets sidor i Dicom‑format.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Initierar en ny instans av klassen `DicomDevice` med standardupplösning. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Initierar en ny instans av klassen `DicomDevice` med angiven sidstorlek, med standardupplösning (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Initierar en ny instans av klassen `DicomDevice`.  Upplösning för den resulterande bildfilen, se [`Resolution`](../resolution/) klass. |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Initierar en ny instans av klassen `DicomDevice` med angivna bilddimensioner, med standardupplösning (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av klassen `DicomDevice` med angiven sidstorlek och upplösning. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av klassen `DicomDevice` med angivna bilddimensioner och upplösning. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Konverterar sidan till Dicom och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

### Se även

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


