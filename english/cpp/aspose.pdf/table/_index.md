---
title: Aspose::Pdf::Table class
linktitle: Table
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Table class. Represents a table that can be added to the page in C++.'
type: docs
weight: 17500
url: /cpp/aspose.pdf/table/
---
## Table class


Represents a table that can be added to the page.

```cpp
class Table : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clone the table. |
| [get_Alignment](./get_alignment/)() const | Gets the table alignment. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets table background color. |
| [get_Border](./get_border/)() const | Gets the border. |
| [get_BreakText](./get_breaktext/)() const | Gets break text for table. |
| [get_Broken](./get_broken/)() const | Gets table vertial broken;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Gets the table column adjustment. |
| [get_ColumnWidths](./get_columnwidths/)() const | Gets the column widths of the table. |
| [get_CornerStyle](./get_cornerstyle/)() const | Gets the styles of the border corners. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Gets default cell border;. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Gets the default cell padding. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Gets the default cell text state. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Gets default cell border;. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Gets border included in column widhts. |
| [get_IsBroken](./get_isbroken/)() const | Gets the table is broken - will be truncated for next page. |
| [get_Left](./get_left/)() const | Gets the table left coordinate. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Gets the maximum columns count for table. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Gets the first rows count repeated for several pages. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Gets the style for repeating rows. |
| [get_Rows](./get_rows/)() const | Gets the rows of the table. |
| [get_Top](./get_top/)() const | Gets the table top coordinate. |
| [GetHeight](./getheight/)(System::SharedPtr\<Page\>) | Get height. |
| [GetWidth](./getwidth/)() | Get width. |
| [set_Alignment](./set_alignment/)(Aspose::Pdf::HorizontalAlignment) | Sets the table alignment. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets table background color. |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets the border. |
| [set_BreakText](./set_breaktext/)(System::SharedPtr\<Text::TextFragment\>) | Sets break text for table. |
| [set_Broken](./set_broken/)(TableBroken) | Sets table vertial broken;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Sets the table column adjustment. |
| [set_ColumnWidths](./set_columnwidths/)(System::String) | Gets the column widths of the table. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Sets the styles of the border corners. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(System::SharedPtr\<BorderInfo\>) | Gets default cell border;. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(System::SharedPtr\<MarginInfo\>) | Sets the default cell padding. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(System::SharedPtr\<Text::TextState\>) | Sets the default cell text state. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(System::String) | Gets default cell border;. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Sets border included in column widhts. |
| [set_IsBroken](./set_isbroken/)(bool) | Sets the table is broken - will be truncated for next page. |
| [set_Left](./set_left/)(float) | Sets the table left coordinate. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Sets the maximum columns count for table. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Gets the first rows count repeated for several pages. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(System::SharedPtr\<Text::TextState\>) | Gets the style for repeating rows. |
| [set_Top](./set_top/)(float) | Sets the table top coordinate. |
| [SetColumnTextState](./setcolumntextstate/)(int32_t, System::SharedPtr\<Text::TextState\>) | Set height. |
| [Table](./table/)() | Default ctor. |
## See Also

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
