---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfExtractor. Представляет базовую функциональность для извлечения текста, изображений и других типов содержимого, которые могут встречаться на страницах PDF-документов
type: docs
weight: 9060
url: /ru/net/aspose.pdf.plugins/pdfextractor/
---
## Класс PdfExtractor

Представляет базовую функциональность для извлечения текста, изображений и других типов содержимого, которые могут встречаться на страницах PDF-документов.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Методы

| Название | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Реализация IDisposable. На самом деле, это не обязательно для PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Запускает обработку PdfExtractor с указанными параметрами. |

## Замечания

Объект [`TextExtractor`](../textextractor/) используется для извлечения текста, а [`ImageExtractor`](../imageextractor/) для извлечения изображений.

## Примеры

Пример демонстрирует, как извлечь текстовое содержимое PDF-документа.

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

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)