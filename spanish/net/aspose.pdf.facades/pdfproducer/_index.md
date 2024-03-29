---
title: PdfProducer
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una clase para producir PDF desde otros formatos.  Este ejemplo muestra cómo producir un archivo PDF a partir de un archivo CGM.
type: docs
weight: 2620
url: /es/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Representa una clase para producir PDF desde otros formatos.  Este ejemplo muestra cómo producir un archivo PDF a partir de un archivo CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Éxito producido archivo pdf.
}
catch (InvalidCgmFileFormatException e)
{
    // Hacer algo...
}
```

```csharp
public abstract class PdfProducer
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce)(Stream, ImportFormat, Stream) | Produce el flujo de PDF utilizando el formato de importación especificado.  Esta muestra muestra cómo producir una transmisión en PDF a partir de una transmisión CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_1)(Stream, ImportFormat, string) | Produce el archivo PDF utilizando el formato de importación especificado.  Este ejemplo muestra cómo producir un archivo PDF desde CGM stream. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_2)(Stream, ImportOptions, Stream) | Produce el archivo PDF utilizando la opción de importación especificada.  Esta muestra muestra cómo producir una transmisión en PDF a partir de una transmisión CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_3)(Stream, ImportOptions, string) | Produce el archivo PDF utilizando la opción de importación especificada.  Este ejemplo muestra cómo producir un archivo PDF desde CGM stream. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_4)(string, ImportFormat, Stream) | Produce el flujo de PDF utilizando el formato de importación especificado.  Este ejemplo muestra cómo producir una transmisión en PDF a partir de un archivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_5)(string, ImportFormat, string) | Produce el archivo PDF utilizando el formato de importación especificado.  Este ejemplo muestra cómo producir un archivo PDF a partir de un archivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_6)(string, ImportOptions, Stream) | Produce el flujo de PDF utilizando la opción de importación especificada.  Este ejemplo muestra cómo producir una transmisión en PDF a partir de un archivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_7)(string, ImportOptions, string) | Produce el archivo PDF utilizando la opción de importación especificada.  Este ejemplo muestra cómo producir un archivo PDF a partir de un archivo CGM. |

### Ver también

* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
