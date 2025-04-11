---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfExtractor. Representa a funcionalidade básica para extrair texto, imagens e outros tipos de conteúdo que podem ocorrer nas páginas de documentos PDF
type: docs
weight: 9060
url: /pt/net/aspose.pdf.plugins/pdfextractor/
---
## Classe PdfExtractor

Representa a funcionalidade básica para extrair texto, imagens e outros tipos de conteúdo que podem ocorrer nas páginas de documentos PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementação de IDisposable. Na verdade, não é necessário para PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Inicia o processamento do PdfExtractor com os parâmetros especificados. |

## Observações

O objeto [`TextExtractor`](../textextractor/) é usado para extrair texto, ou [`ImageExtractor`](../imageextractor/) para extrair imagens.

## Exemplos

O exemplo demonstra como extrair o conteúdo de texto de um documento PDF.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)