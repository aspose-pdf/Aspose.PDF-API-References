---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.ImageExtractor. Representa el plugin ImageExtractor
type: docs
weight: 8890
url: /es/net/aspose.pdf.plugins/imageextractor/
---
## Clase ImageExtractor

Representa el plugin ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageExtractor](imageextractor/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementación de IDisposable. En realidad, no es necesario para PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Inicia el procesamiento de PdfExtractor con los parámetros especificados. |

## Observaciones

El objeto `ImageExtractor` se utiliza para extraer texto en documentos PDF.

## Ejemplos

El ejemplo demuestra cómo extraer imágenes de un documento PDF.

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Ver También

* clase [PdfExtractor](../pdfextractor/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)