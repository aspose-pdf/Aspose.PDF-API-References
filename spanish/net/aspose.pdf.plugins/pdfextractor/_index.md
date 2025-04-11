---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PdfExtractor. Representa la funcionalidad base para extraer texto, imágenes y otros tipos de contenido que pueden ocurrir en las páginas de documentos PDF
type: docs
weight: 9060
url: /es/net/aspose.pdf.plugins/pdfextractor/
---
## Clase PdfExtractor

Representa la funcionalidad base para extraer texto, imágenes y otros tipos de contenido que pueden ocurrir en las páginas de documentos PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementación de IDisposable. En realidad, no es necesario para PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Inicia el procesamiento de PdfExtractor con los parámetros especificados. |

## Observaciones

El objeto [`TextExtractor`](../textextractor/) se utiliza para extraer texto, o [`ImageExtractor`](../imageextractor/) para extraer imágenes.

## Ejemplos

El ejemplo demuestra cómo extraer el contenido de texto de un documento PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Véase también

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)