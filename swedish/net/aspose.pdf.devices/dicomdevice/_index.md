---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DicomDevice klass. Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i Dicom-format
type: docs
weight: 3560
url: /sv/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice klass

Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i Dicom-format.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Initierar en ny instans av `DicomDevice` klassen med standardupplösning. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Initierar en ny instans av `DicomDevice` klassen med angiven sidstorlek, med standardupplösning (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Initierar en ny instans av `DicomDevice` klassen. Upplösning för den resulterande bildfilen, se [`Resolution`](../resolution/) klass. |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Initierar en ny instans av `DicomDevice` klassen med angivna bilddimensioner, med standardupplösning (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av `DicomDevice` klassen med angiven sidstorlek och upplösning. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av `DicomDevice` klassen med angivna bilddimensioner och upplösning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller sätter sidkoordinattype (Media/Crop boxes). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utmatningshöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller sätter renderingalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utmatningsbredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Konverterar sidan till Dicom och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

### Se Även

* klass [ImageDevice](../imagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)