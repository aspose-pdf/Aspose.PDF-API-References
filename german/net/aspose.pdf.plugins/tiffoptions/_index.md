---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions-Klasse. Stellt die Optionen für den Pdf zu Tiff-Konverter für das Tiff-Plugin dar
type: docs
weight: 9420
url: /de/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions-Klasse

Stellt die Optionen für den Pdf zu Tiff-Konverter für das [`Tiff`](../tiff/) Plugin dar.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Ruft einen Wertbereich der Transformation von Farben in Weiß und Schwarz ab oder legt ihn fest. Dieser Parameter kann mit EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle oder ColorDepth.Format1bpp == 1 angewendet werden. |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Ruft den Typ der Kompression ab oder legt ihn fest. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Ruft den Bildkonvertierungsmodus ab. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Ruft die Farbtiefe ab oder legt sie fest. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Gibt die Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins zurück. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Gibt den Namen der Operation zurück. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ruft den Auflösungswert der resultierenden Bilder ab oder legt ihn fest. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ruft eine Liste von Seiten für den Prozess ab oder legt sie fest. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Ruft ein Flag ab und legt es fest, das es ermöglicht, alle Seiten in einem mehrseitigen Tiff zu speichern. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Ruft den Typ der Form ab oder legt ihn fest. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob leere Seiten übersprungen werden sollen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Fügt der Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Legt eine neue Speicher-Datenquelle fest. Kann nur eine . sein. Wenn Sie Bilder in Speicherstreams speichern möchten, übergeben Sie null als Parameter. |

### Siehe auch

* Klasse [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)