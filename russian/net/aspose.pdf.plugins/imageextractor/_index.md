---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.ImageExtractor. Представляет плагин ImageExtractor
type: docs
weight: 8890
url: /ru/net/aspose.pdf.plugins/imageextractor/
---
## Класс ImageExtractor

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Реализация IDisposable. На самом деле, это не обязательно для PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Запускает обработку PdfExtractor с указанными параметрами. |

## Замечания

Объект `ImageExtractor` используется для извлечения текста в PDF-документах.

## Примеры

Пример демонстрирует, как извлечь изображения из PDF-документа.

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

### См. также

* класс [PdfExtractor](../pdfextractor/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)