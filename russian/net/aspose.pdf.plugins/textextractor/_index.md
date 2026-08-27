---
title: "Класс TextExtractor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.TextExtractor. Представляет плагин TextExtractor"
type: docs
weight: 9530
url: /ru/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Реализация IDisposable. На самом деле, это не требуется для PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Запускает обработку PdfExtractor с указанными параметрами. |

## Примечания

Объект `TextExtractor` используется для извлечения текста из PDF‑документов.

## Примеры

Пример демонстрирует, как извлечь текстовое содержимое PDF‑документа.

```csharp
// создать объект TextExtractor для извлечения текста из содержимого PDF
using (TextExtractor extractor = new TextExtractor())
{
    // создать TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // добавьте путь входного файла в источники данных
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // выполнить процесс извлечения
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // получите извлечённый текст из объекта ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### См. также

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


