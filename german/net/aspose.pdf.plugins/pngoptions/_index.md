---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PngOptions-Klasse. Stellt Optionen für den Pdf zu Png-Konverter für das Png-Plugin dar
type: docs
weight: 9180
url: /de/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions-Klasse

Stellt Optionen für den Pdf zu Png-Konverter für das [`Png`](../png/) Plugin dar.

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PngOptions](pngoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Gibt den Bildkonvertierungsmodus zurück. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Gibt die Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins zurück. |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Gibt den Namen der Operation zurück. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Gibt den oder setzt den Auflösungswert der resultierenden Bilder. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Gibt eine Liste von Seiten für den Prozess zurück oder setzt diese. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Fügt der Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Setzt eine neue Speicher-Datenquelle. Kann nur eine . sein. Wenn Sie Bilder in den Arbeitsspeicher-Streams speichern möchten, übergeben Sie null als Parameter. |

### Siehe auch

* Klasse [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)