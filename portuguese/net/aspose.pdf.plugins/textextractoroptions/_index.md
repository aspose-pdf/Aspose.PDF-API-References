---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TextExtractorOptions. Representa opções de extração de texto para o plugin TextExtractor
type: docs
weight: 9390
url: /pt/net/aspose.pdf.plugins/textextractoroptions/
---
## Classe TextExtractorOptions

Representa opções de extração de texto para o plugin TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Inicializa uma nova instância do objeto `TextExtractorOptions` com o modo de formatação de texto 'Raw' (padrão). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Inicializa uma nova instância do objeto `TextExtractorOptions` para o modo de formatação de texto especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Obtém o modo de formatação. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Retorna a coleção de dados do plugin PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Retorna o nome da operação. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Adiciona uma nova fonte de dados à coleção de dados do plugin PdfExtractor. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Define diferentes modos que podem ser usados ao converter um documento PDF em texto. Veja a classe `TextExtractorOptions`. |

## Observações

O objeto `TextExtractorOptions` é usado para definir [`TextFormattingMode`](../textextractoroptions.textformattingmode/) e outras opções para a operação de extração de texto. Além disso, herda funções para adicionar dados (arquivos, fluxos) representando documentos PDF de entrada.

## Exemplos

O exemplo demonstra como extrair o conteúdo de texto de um documento PDF.

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

### Veja Também

* classe [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)