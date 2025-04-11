---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToImageOptions-Klasse. Stellt Optionen für das PdfToImage-Plugin dar
type: docs
weight: 9130
url: /de/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions-Klasse

Stellt Optionen für das [`PdfToImage`](../pdftoimage/) Plugin dar.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Gibt den Bildkonvertierungsmodus zurück. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Gibt die Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins zurück. |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Gibt den Namen der Operation zurück. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Gibt den Auflösungswert der resultierenden Bilder zurück oder setzt ihn. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Gibt eine Liste von Seiten für den Prozess zurück oder setzt sie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Fügt der Datensammlung des [`PdfToImage`](../pdftoimage/) Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Setzt eine neue Speicher-Datenquelle. Kann nur eine sein. Wenn Sie Bilder in Speicherstreams speichern möchten, übergeben Sie null als Parameter. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Definiert verschiedene Modi, die beim Konvertieren von PDF-Dokumenten in Jpeg-Bilder verwendet werden können. Siehe die [`JpegOptions`](../jpegoptions/) Klasse. |

## Anmerkungen

Die PdfImageOptions-Klasse enthält grundlegende Funktionen zum Hinzufügen von Daten (Dateien, Streams), die Eingabe-PDF-Dokumente darstellen.

### Siehe auch

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)