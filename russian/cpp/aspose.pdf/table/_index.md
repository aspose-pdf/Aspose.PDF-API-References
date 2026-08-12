---
title: "Класс Aspose::Pdf::Table"
linktitle: "Table"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Table. Представляет таблицу, которую можно добавить на страницу в C++."
type: docs
weight: 17700
url: /ru/cpp/aspose.pdf/table/
---
## Table class


Представляет таблицу, которую можно добавить на страницу.

```cpp
class Table : public Aspose::Pdf::BaseParagraph
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонировать таблицу. |
| [get_Alignment](./get_alignment/)() const | Получает выравнивание таблицы. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Получает цвет фона таблицы. |
| [get_Border](./get_border/)() const | Получает границу. |
| [get_BreakText](./get_breaktext/)() const | Получает разрыв текста для таблицы. |
| [get_Broken](./get_broken/)() const | Получает вертикальное разбиение таблицы;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Получает настройку столбцов таблицы. |
| [get_ColumnWidths](./get_columnwidths/)() const | Получает ширины столбцов таблицы. |
| [get_CornerStyle](./get_cornerstyle/)() const | Получает стили углов границы. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Получает границу ячейки по умолчанию;. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Получает отступ ячейки по умолчанию. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Получает состояние текста ячейки по умолчанию. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Получает границу ячейки по умолчанию;. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Получает границу, включённую в ширину столбцов. |
| [get_IsBroken](./get_isbroken/)() const | Получает, что таблица разорвана — будет обрезана на следующей странице. |
| [get_Left](./get_left/)() const | Получает левую координату таблицы. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Получает максимальное количество столбцов в таблице. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Получает количество первых строк, повторяемых на нескольких страницах. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Получает стиль повторяющихся строк. |
| [get_Rows](./get_rows/)() const | Получает строки таблицы. |
| [get_Top](./get_top/)() const | Получает верхнюю координату таблицы. |
| [GetHeight](./getheight/)(const System::SharedPtr\<Page\>\&) | Получить высоту. |
| [GetWidth](./getwidth/)() | Получить ширину. |
| [set_Alignment](./set_alignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает выравнивание таблицы. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Устанавливает цвет фона таблицы. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Устанавливает границу. |
| [set_BreakText](./set_breaktext/)(const System::SharedPtr\<Text::TextFragment\>\&) | Устанавливает текст разрыва для таблицы. |
| [set_Broken](./set_broken/)(TableBroken) | Устанавливает вертикальный разрыв таблицы;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Устанавливает настройку столбцов таблицы. |
| [set_ColumnWidths](./set_columnwidths/)(const System::String\&) | Получает ширины столбцов таблицы. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Устанавливает стили углов границы. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(const System::SharedPtr\<BorderInfo\>\&) | Получает границу ячейки по умолчанию;. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает отступ ячейки по умолчанию. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Устанавливает состояние текста ячейки по умолчанию. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(const System::String\&) | Получает границу ячейки по умолчанию;. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Устанавливает границу, включённую в ширину столбцов. |
| [set_IsBroken](./set_isbroken/)(bool) | Устанавливает, что таблица разорвана — будет обрезана на следующей странице. |
| [set_Left](./set_left/)(float) | Устанавливает левую координату таблицы. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Устанавливает максимальное количество столбцов в таблице. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Получает количество первых строк, повторяемых на нескольких страницах. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(const System::SharedPtr\<Text::TextState\>\&) | Получает стиль повторяющихся строк. |
| [set_Top](./set_top/)(float) | Устанавливает верхнюю координату таблицы. |
| [SetColumnTextState](./setcolumntextstate/)(int32_t, const System::SharedPtr\<Text::TextState\>\&) | Установить высоту. |
| [Table](./table/)() | Конструктор по умолчанию. |
## См. также

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
