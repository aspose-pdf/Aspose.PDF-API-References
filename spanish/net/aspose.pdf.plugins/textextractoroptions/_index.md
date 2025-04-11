---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.TextExtractorOptions. Representa opciones de extracción de texto para el plugin TextExtractor
type: docs
weight: 9390
url: /es/net/aspose.pdf.plugins/textextractoroptions/
---
## Clase TextExtractorOptions

Representa opciones de extracción de texto para el plugin TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Inicializa una nueva instancia del objeto `TextExtractorOptions` con el modo de formato de texto 'Raw' (predeterminado). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Inicializa una nueva instancia del objeto `TextExtractorOptions` para el modo de formato de texto especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Obtiene el modo de formato. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Devuelve la colección de datos del plugin PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Devuelve el nombre de la operación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del plugin PdfExtractor. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Define diferentes modos que se pueden utilizar al convertir un documento PDF en texto. Ver clase `TextExtractorOptions`. |

## Observaciones

El objeto `TextExtractorOptions` se utiliza para establecer [`TextFormattingMode`](../textextractoroptions.textformattingmode/) y otras opciones para la operación de extracción de texto. Además, hereda funciones para agregar datos (archivos, flujos) que representan documentos PDF de entrada.

## Ejemplos

El ejemplo demuestra cómo extraer el contenido de texto de un documento PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Ver También

* clase [PdfExtractorOptions](../pdfextractoroptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)