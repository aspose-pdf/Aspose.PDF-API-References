---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfProducer-Klasse. Stellt eine Klasse dar, um PDF aus anderen Formaten zu erzeugen. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einer CGM-Datei erzeugt.
type: docs
weight: 4610
url: /de/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer-Klasse

Stellt eine Klasse dar, um PDF aus anderen Formaten zu erzeugen. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einer CGM-Datei erzeugt.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Success produced pdf file.
}
catch (InvalidCgmFileFormatException e)
{
    //  Do something...
}
```

```csharp
public abstract class PdfProducer
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Erzeugt den PDF-Stream unter Verwendung des angegebenen Importformats. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einem CGM-Stream erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Erzeugt die PDF-Datei unter Verwendung des angegebenen Importformats. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einem CGM-Stream erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Erzeugt die PDF-Datei unter Verwendung der angegebenen Importoption. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einem CGM-Stream erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Erzeugt die PDF-Datei unter Verwendung der angegebenen Importoption. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einem CGM-Stream erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Erzeugt den PDF-Stream unter Verwendung des angegebenen Importformats. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einer CGM-Datei erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Erzeugt die PDF-Datei unter Verwendung des angegebenen Importformats. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einer CGM-Datei erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Erzeugt den PDF-Stream unter Verwendung der angegebenen Importoption. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einer CGM-Datei erzeugt. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Erzeugt die PDF-Datei unter Verwendung der angegebenen Importoption. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einer CGM-Datei erzeugt. |

### Siehe auch

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)