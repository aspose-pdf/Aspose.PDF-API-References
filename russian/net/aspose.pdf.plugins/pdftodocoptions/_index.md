---
title: Class PdfToDocOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfToDocOptions. Представляет параметры конвертации PDF в DOC для плагина DocConverter
type: docs
weight: 9090
url: /ru/net/aspose.pdf.plugins/pdftodocoptions/
---
## Класс PdfToDocOptions

Представляет параметры конвертации PDF в DOC для плагина [`DocConverter`](../docconverter/).

```csharp
public sealed class PdfToDocOptions : PdfConverterOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfToDocOptions](pdftodocoptions/#constructor)() | Инициализирует новый экземпляр объекта `PdfToDocOptions` с параметрами по умолчанию. |
| [PdfToDocOptions](pdftodocoptions/#constructor_1)(SaveFormat, ConversionMode) | Инициализирует новый экземпляр объекта `PdfToDocOptions` для указанного формата и режима. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftodocoptions/conversionmode/) { get; set; } | Позволяет контролировать, как PDF-документ конвертируется в документ обработки текста. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Возвращает коллекцию данных плагина PdfConverterOptions. |
| override [OperationName](../../aspose.pdf.plugins/pdftodocoptions/operationname/) { get; } | Получает имя операции. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Получает коллекцию добавленных целей для сохранения результатов операции. |
| [SaveFormat](../../aspose.pdf.plugins/pdftodocoptions/saveformat/) { get; set; } | Формат сохранения выходного документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfToXLSXConverterOptions. |

### См. также

* класс [PdfConverterOptions](../pdfconverteroptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)