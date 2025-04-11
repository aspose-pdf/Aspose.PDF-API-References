---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfExtractorOptions. Представляет параметры для плагинов TextExtractor и ImageExtractor
type: docs
weight: 9070
url: /ru/net/aspose.pdf.plugins/pdfextractoroptions/
---
## Класс PdfExtractorOptions

Представляет параметры для плагинов TextExtractor и ImageExtractor.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Возвращает коллекцию данных плагина PdfExtractor. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | Возвращает имя операции |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfExtractor. |

## Замечания

`PdfExtractorOptions` содержит базовые функции для добавления данных (файлов, потоков), представляющих входные PDF-документы. Пожалуйста, создайте [`TextExtractorOptions`](../textextractoroptions/) или ImageExtractorOptions вместо этого.

### См. также

* интерфейс [IPluginOptions](../ipluginoptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)