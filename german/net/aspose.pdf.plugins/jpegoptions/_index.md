---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions-Klasse. Stellt Optionen für den Pdf-zu-Jpeg-Konverter für das Jpeg-Plugin dar
type: docs
weight: 8920
url: /de/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions-Klasse

Stellt Optionen für den Pdf-zu-Jpeg-Konverter für das [`Jpeg`](../jpeg/) Plugin dar.

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [JpegOptions](jpegoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Gibt den Bildkonvertierungsmodus zurück. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Gibt die Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins zurück. |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Gibt den Namen der Operation zurück. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Gibt den Auflösungswert der resultierenden Bilder zurück oder setzt ihn. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Gibt eine Liste von Seiten für den Prozess zurück oder setzt sie. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Gibt die Jpeg-Qualität zurück und setzt sie |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Fügt der Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Setzt eine neue Speicher-Datenquelle. Kann nur eine . sein. Wenn Sie Bilder in den Arbeitsspeicher-Streams speichern möchten, übergeben Sie null als Parameter. |

### Siehe auch

* Klasse [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)