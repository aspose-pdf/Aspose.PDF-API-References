---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TextExtractor. Representa o plugin TextExtractor
type: docs
weight: 9380
url: /pt/net/aspose.pdf.plugins/textextractor/
---
## Classe TextExtractor

Representa o plugin TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextExtractor](textextractor/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementação de IDisposable. Na verdade, não é necessário para PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Inicia o processamento do PdfExtractor com os parâmetros especificados. |

## Observações

O objeto `TextExtractor` é usado para extrair texto em documentos PDF.

## Exemplos

O exemplo demonstra como extrair o conteúdo de texto de um documento PDF.

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

### Veja Também

* classe [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)