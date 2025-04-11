---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.TextExtractorOptions. Представляет параметры извлечения текста для плагина TextExtractor
type: docs
weight: 9390
url: /ru/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

Представляет параметры извлечения текста для плагина TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Инициализирует новый экземпляр объекта `TextExtractorOptions` с режимом форматирования текста 'Raw' (по умолчанию). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Инициализирует новый экземпляр объекта `TextExtractorOptions` для указанного режима форматирования текста. |

## Properties

| Name | Description |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Получает режим форматирования. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Возвращает коллекцию данных плагина PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Возвращает имя операции. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfExtractor. |

## Other Members

| Name | Description |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Определяет различные режимы, которые могут быть использованы при преобразовании PDF-документа в текст. См. класс `TextExtractorOptions`. |

## Remarks

Объект `TextExtractorOptions` используется для установки [`TextFormattingMode`](../textextractoroptions.textformattingmode/) и других параметров для операции извлечения текста. Кроме того, он наследует функции для добавления данных (файлов, потоков), представляющих входные PDF-документы.

## Examples

Пример демонстрирует, как извлечь текстовое содержимое PDF-документа.

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

### See Also

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)