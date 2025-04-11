---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.TextExtractor. Представляет плагин TextExtractor
type: docs
weight: 9380
url: /ru/net/aspose.pdf.plugins/textextractor/
---
## Класс TextExtractor

Представляет плагин TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextExtractor](textextractor/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Реализация IDisposable. На самом деле, это не обязательно для PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Запускает обработку PdfExtractor с указанными параметрами. |

## Замечания

Объект `TextExtractor` используется для извлечения текста из PDF-документов.

## Примеры

Пример демонстрирует, как извлечь текстовое содержимое PDF-документа.

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

### См. также

* класс [PdfExtractor](../pdfextractor/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)