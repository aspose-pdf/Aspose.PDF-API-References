---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfProducer. Representa una clase para producir PDF a partir de otros formatos. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM
type: docs
weight: 4610
url: /es/net/aspose.pdf.facades/pdfproducer/
---
## Clase PdfProducer

Representa una clase para producir PDF a partir de otros formatos. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Produce el flujo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un flujo Pdf a partir de un flujo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Produce el archivo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un archivo Pdf a partir de un flujo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Produce el archivo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un flujo Pdf a partir de un flujo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Produce el archivo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un archivo Pdf a partir de un flujo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Produce el flujo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un flujo Pdf a partir de un archivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Produce el archivo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Produce el flujo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un flujo Pdf a partir de un archivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Produce el archivo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM. |

### Ver También

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)