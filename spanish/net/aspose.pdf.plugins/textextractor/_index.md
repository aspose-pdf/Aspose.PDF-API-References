---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.TextExtractor. Representa el plugin TextExtractor
type: docs
weight: 9380
url: /es/net/aspose.pdf.plugins/textextractor/
---
## Clase TextExtractor

Representa el plugin TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextExtractor](textextractor/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementación de IDisposable. En realidad, no es necesario para PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Inicia el procesamiento de PdfExtractor con los parámetros especificados. |

## Observaciones

El objeto `TextExtractor` se utiliza para extraer texto en documentos PDF.

## Ejemplos

El ejemplo demuestra cómo extraer el contenido de texto de un documento PDF.

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Ver También

* clase [PdfExtractor](../pdfextractor/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)