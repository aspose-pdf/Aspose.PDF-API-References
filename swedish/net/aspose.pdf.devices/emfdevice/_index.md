---
title: EmfDevice
second_title: Aspose.PDF för .NET API Referens
description: Representerar bildenhet som hjälper till att spara pdf-dokumentsidor i emf.
type: docs
weight: 1680
url: /sv/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

Representerar bildenhet som hjälper till att spara pdf-dokumentsidor i emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfDevice](emfdevice#constructor)() | Initierar en ny instans av[`EmfDevice`](../emfdevice) klass med standardupplösning för rasterbild skriven till emf. |
| [EmfDevice](emfdevice#constructor_2)(PageSize) | Initierar en ny instans av[`EmfDevice`](../emfdevice) klass med angiven sidstorlek, och standardupplösning för rasterbilden skriven till emf (=150) |
| [EmfDevice](emfdevice#constructor_1)(Resolution) | Initierar en ny instans av[`EmfDevice`](../emfdevice) class.  Upplösning för rasterbilden skriven till emf, se[`Resolution`](../resolution) class. |
| [EmfDevice](emfdevice#constructor_4)(int, int) | Initierar en ny instans av[`EmfDevice`](../emfdevice) klass med angivna bildmått, och standardupplösning för rasterbilden skriven till emf (=150) |
| [EmfDevice](emfdevice#constructor_3)(PageSize, Resolution) | Initierar en ny instans av[`JpegDevice`](../jpegdevice)klass med angiven sidstorlek, och upplösning för rasterbilden skriven till emf. |
| [EmfDevice](emfdevice#constructor_5)(int, int, Resolution) | Initierar en ny instans av[`JpegDevice`](../jpegdevice) klass med angivna bildmått, och upplösning för rasterbilden skriven till emf. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Hämtar eller ställer in sidkoordinattypen (Media/Crop-rutor). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Hämtar eller ställer in formulärpresentationsläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Får bildutgångshöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Hämtar eller ställer in renderingsalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Får bildupplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Får bildutdatabredd. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process#process)(Page, Stream) | Konverterar sidan till emf och sparar den i utdataströmmen. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Utför någon operation på den givna sidan och sparar resultat i filen. |

### Se även

* class [ImageDevice](../imagedevice)
* namnutrymme [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->