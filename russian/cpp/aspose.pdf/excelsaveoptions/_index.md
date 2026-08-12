---
title: "Aspose::Pdf::ExcelSaveOptions класс"
linktitle: "ExcelSaveOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::ExcelSaveOptions класс. Параметры сохранения для экспорта в формат Excel в C++."
type: docs
weight: 4700
url: /ru/cpp/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class


Параметры сохранения для экспорта в формат Excel.

```cpp
class ExcelSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ExcelFormat](./excelformat/) | Позволяет указать формат файлов .xlsx, .xls/xml или csv. Значение по умолчанию — XLSX;. |
## Методы

| Метод | Описание |
| --- | --- |
| [ExcelSaveOptions](./excelsaveoptions/)() | Конструктор. |
| [get_Format](./get_format/)() const | Формат вывода. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Установите true, если необходимо вставить пустой столбец в качестве первого столбца листа. Значение по умолчанию — false; это означает, что пустой столбец не будет вставлен. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Установите true, если необходимо минимизировать количество листов в результирующей книге. Значение по умолчанию — false; это означает сохранение каждой страницы PDF как отдельного листа. |
| [get_UniformWorksheets](./get_uniformworksheets/)() const | Установите true для использования равномерного деления столбцов по всему документу. Значение по умолчанию — false; это означает, что деление столбцов будет независимым для каждой страницы. |
| [set_Format](./set_format/)(ExcelSaveOptions::ExcelFormat) | Формат вывода. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Установите true, если необходимо вставить пустой столбец в качестве первого столбца листа. Значение по умолчанию — false; это означает, что пустой столбец не будет вставлен. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Установите true, если необходимо минимизировать количество листов в результирующей книге. Значение по умолчанию — false; это означает сохранение каждой страницы PDF как отдельного листа. |
| [set_UniformWorksheets](./set_uniformworksheets/)(bool) | Установите true для использования равномерного деления столбцов по всему документу. Значение по умолчанию — false; это означает, что деление столбцов будет независимым для каждой страницы. |
## См. также

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
