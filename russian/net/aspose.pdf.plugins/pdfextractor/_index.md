---
title: "Класс PdfExtractor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.PdfExtractor класс. Представляет базовую функциональность для извлечения текста, изображений и других типов контента, которые могут встречаться на страницах PDF‑документов"
type: docs
weight: 9210
url: /ru/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

Представляет базовую функциональность для извлечения текста, изображений и других типов содержимого, которые могут находиться на страницах PDF‑документов.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Реализация IDisposable. На самом деле, это не требуется для PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Запускает обработку PdfExtractor с указанными параметрами. |

## Примечания

Объект [`TextExtractor`](../textextractor/) используется для извлечения текста, а [`ImageExtractor`](../imageextractor/) — для извлечения изображений.

## Примеры

Пример демонстрирует, как извлечь текстовое содержимое PDF‑документа.

```csharp
// создайте объект TextExtractor для извлечения содержимого PDF
using (TextExtractor extractor = new TextExtractor())
{
    // создайте объект TextExtractorOptions, чтобы задать инструкции
    textExtractorOptions = new TextExtractorOptions();
    
    // добавьте путь входного файла в источники данных
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // выполнить процесс извлечения
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // получите извлечённый текст из объекта ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


