---
title: "Класс Aspose::Pdf::LowCode::PdfToXlsOptions"
linktitle: "PdfToXlsOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::PdfToXlsOptions. Представляет параметры конвертера PDF в XLSX для плагина XlsConverter в C++."
type: docs
weight: 6600
url: /ru/cpp/aspose.pdf.lowcode/pdftoxlsoptions/
---
## PdfToXlsOptions class


Представляет параметры конвертера PDF в XLSX для плагина [XlsConverter](../xlsconverter/).

```cpp
class PdfToXlsOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ExcelFormat](./excelformat/) | Позволяет указать формат файлов .xlsx, .xls/xml или csv. Значение по умолчанию — XLSX. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_Format](./get_format/)() const | Формат вывода. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Установите true, если необходимо вставить пустой столбец в качестве первого столбца листа. Значение по умолчанию — false; это означает, что пустой столбец не будет вставлен. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Установите true, если необходимо минимизировать количество листов в результирующей книге. Значение по умолчанию — false; это означает сохранение каждой страницы PDF как отдельного листа. |
| [get_OperationName](./get_operationname/)() override | Получает имя операции. |
| [PdfToXlsOptions](./pdftoxlsoptions/)() | Инициализирует новый экземпляр объекта [PdfToXlsOptions](./) с параметрами по умолчанию. |
| [set_Format](./set_format/)(PdfToXlsOptions::ExcelFormat) | Формат вывода. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Установите true, если необходимо вставить пустой столбец в качестве первого столбца листа. Значение по умолчанию — false; это означает, что пустой столбец не будет вставлен. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Установите true, если необходимо минимизировать количество листов в результирующей книге. Значение по умолчанию — false; это означает сохранение каждой страницы PDF как отдельного листа. |
## См. также

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
