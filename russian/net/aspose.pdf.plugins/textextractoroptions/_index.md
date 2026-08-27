---
title: "Класс TextExtractorOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.TextExtractorOptions class. Представляет параметры извлечения текста для плагина TextExtractor."
type: docs
weight: 9540
url: /ru/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

Представляет параметры извлечения текста для плагина TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Инициализирует новый экземпляр объекта `TextExtractorOptions` с режимом форматирования текста 'Raw' (по умолчанию). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Инициализирует новый экземпляр объекта `TextExtractorOptions` для указанного режима форматирования текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Получает режим форматирования. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Возвращает коллекцию данных плагина PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Возвращает название операции. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfExtractor. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Определяет различные режимы, которые могут использоваться при преобразовании PDF‑документа в текст. См. класс `TextExtractorOptions`. |

## Примечания

Объект `TextExtractorOptions` используется для установки [`TextFormattingMode`](../textextractoroptions.textformattingmode/) и других параметров операции извлечения текста. Кроме того, он наследует функции добавления данных (файлов, потоков), представляющих входные PDF‑документы.

## Примеры

Пример демонстрирует, как извлечь текстовое содержимое PDF‑документа.

```csharp
// создайте объект TextExtractor для извлечения содержимого PDF
using (TextExtractor extractor = new TextExtractor())
{
    // создайте объект TextExtractorOptions для установки TextFormattingMode (Pure,  или Raw — по умолчанию)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // добавьте путь входного файла в источники данных
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // выполнить процесс извлечения
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // получите извлечённый текст из объекта ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### См. также

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


