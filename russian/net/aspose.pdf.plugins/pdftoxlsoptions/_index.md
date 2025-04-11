---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfToXlsOptions. Представляет параметры конвертации PDF в XLSX для плагина XlsConverter
type: docs
weight: 9150
url: /ru/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## Класс PdfToXlsOptions

Представляет параметры конвертации PDF в XLSX для плагина [`XlsConverter`](../xlsconverter/).

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Формат вывода. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Возвращает коллекцию данных плагина PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Установите true, если необходимо вставить пустой столбец в качестве первого столбца рабочего листа. Значение по умолчанию - false; это означает, что пустой столбец не будет вставлен. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Установите true, если необходимо минимизировать количество рабочих листов в результирующей книге. Значение по умолчанию - false; это означает сохранение каждой страницы PDF как отдельного рабочего листа. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Получает имя операции. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Получает коллекцию добавленных целей для сохранения результатов операции. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfToXLSXConverterOptions. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Позволяет указать формат файла .xlsx, .xls/xml или csv. Значение по умолчанию - XLSX. |

### См. также

* класс [PdfConverterOptions](../pdfconverteroptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)