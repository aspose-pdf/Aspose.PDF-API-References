---
title: "Aspose::Pdf::LogicalStructure::TableElement класс"
linktitle: "TableElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::TableElement класс. Представляет элемент структуры Table в логической структуре на C++."
type: docs
weight: 6200
url: /ru/cpp/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class


Представляет элемент структуры [Table](../../aspose.pdf/table/) в логической структуре.

```cpp
class TableElement : public Aspose::Pdf::LogicalStructure::BLSElement,
                     public Aspose::Pdf::Tagged::IAdjustPosition
```

## Методы

| Метод | Описание |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [CreateTBody](./createtbody/)() | Создаёт [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) и добавляет его в текущую таблицу. |
| [CreateTFoot](./createtfoot/)() | Создаёт [Aspose::Pdf::LogicalStructure::TableTFootElement](../tabletfootelement/) и добавляет его в текущую таблицу. |
| [CreateTHead](./createthead/)() | Создаёт [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) и добавляет его в текущую таблицу. |
| [get_Alignment](./get_alignment/)() const | Получает выравнивание таблицы. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Получает цвет фона таблицы. |
| [get_Border](./get_border/)() const | Получает границу таблицы. |
| [get_Broken](./get_broken/)() const | Получает вертикальное разбиение таблицы;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Получает настройку столбцов таблицы. |
| [get_ColumnWidths](./get_columnwidths/)() const | Получает ширины столбцов таблицы. |
| [get_CornerStyle](./get_cornerstyle/)() const | Получает стили углов границы. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Получает границу ячейки по умолчанию. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Получает отступ ячейки по умолчанию. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Получает состояние текста ячейки по умолчанию. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Получает ширину столбца по умолчанию. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Получает границу, включённую в ширину столбцов. |
| [get_IsBroken](./get_isbroken/)() const | Получает, что таблица разорвана — будет обрезана на следующей странице. |
| [get_Left](./get_left/)() const | Получает левую координату таблицы. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Получает максимальное количество столбцов в таблице. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Получает количество первых строк, повторяемых на нескольких страницах. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Получает стиль повторяющихся строк. |
| [get_Top](./get_top/)() const | Получает верхнюю координату таблицы. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Устанавливает выравнивание таблицы. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Устанавливает цвет фона таблицы. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Устанавливает границу таблицы. |
| [set_Broken](./set_broken/)(TableBroken) | Устанавливает вертикальный разрыв таблицы;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Устанавливает настройку столбцов таблицы. |
| [set_ColumnWidths](./set_columnwidths/)(const System::String\&) | Получает ширины столбцов таблицы. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Устанавливает стили углов границы. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(const System::SharedPtr\<BorderInfo\>\&) | Получает границу ячейки по умолчанию. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает отступ ячейки по умолчанию. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Устанавливает состояние текста ячейки по умолчанию. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(const System::String\&) | Устанавливает ширину столбца по умолчанию. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Устанавливает границу, включённую в ширину столбцов. |
| [set_IsBroken](./set_isbroken/)(bool) | Устанавливает, что таблица разорвана — будет обрезана на следующей странице. |
| [set_Left](./set_left/)(float) | Устанавливает левую координату таблицы. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Устанавливает максимальное количество столбцов в таблице. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Получает количество первых строк, повторяемых на нескольких страницах. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(const System::SharedPtr\<Text::TextState\>\&) | Получает стиль повторяющихся строк. |
| [set_Top](./set_top/)(float) | Устанавливает верхнюю координату таблицы. |
## См. также

* Class [BLSElement](../blselement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
