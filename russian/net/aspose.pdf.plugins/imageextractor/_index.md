---
title: "Класс ImageExtractor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.ImageExtractor класс. Представляет плагин ImageExtractor"
type: docs
weight: 9020
url: /ru/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

Представляет плагин ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Реализация IDisposable. На самом деле, это не требуется для PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Запускает обработку PdfExtractor с указанными параметрами. |

## Примечания

Объект `ImageExtractor` используется для извлечения текста в PDF‑документах.

## Примеры

В примере демонстрируется, как извлекать изображения из PDF‑документа.

```csharp
// создайте объект ImageExtractor для извлечения изображений
using (ImageExtractor extractor = new ImageExtractor())
{
    // создайте ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // добавьте путь входного файла в источники данных
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // выполнить процесс извлечения
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // получите изображение из объекта ResultContainer
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### См. также

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


