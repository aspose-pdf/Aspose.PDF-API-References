---
title: "Aspose::Pdf::Table class"
linktitle: "Tabell"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Table-klass. Representerar en tabell som kan läggas till på sidan i C++."
type: docs
weight: 17700
url: /sv/cpp/aspose.pdf/table/
---
## Table class


Representerar en tabell som kan läggas till på sidan.

```cpp
class Table : public Aspose::Pdf::BaseParagraph
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klona tabellen. |
| [get_Alignment](./get_alignment/)() const | Hämtar tabellens justering. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Hämtar tabellens bakgrundsfärg. |
| [get_Border](./get_border/)() const | Hämtar kanten. |
| [get_BreakText](./get_breaktext/)() const | Hämtar radbrytningstext för tabellen. |
| [get_Broken](./get_broken/)() const | Hämtar tabellens vertikala avbrott;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Hämtar tabellens kolumnjustering. |
| [get_ColumnWidths](./get_columnwidths/)() const | Hämtar kolumnbredderna i tabellen. |
| [get_CornerStyle](./get_cornerstyle/)() const | Hämtar stilarna för kantens hörn. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Hämtar standardcellram;. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Hämtar standardcellens fyllnad. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Hämtar standardtexttillståndet för cellen. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Hämtar standardcellram;. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Hämtar kant inkluderad i kolumnbredder. |
| [get_IsBroken](./get_isbroken/)() const | Hämtar om tabellen är avbruten – kommer att trunkeras för nästa sida. |
| [get_Left](./get_left/)() const | Hämtar tabellens vänstra koordinat. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Hämtar maximalt antal kolumner för tabellen. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Hämtar antalet första rader som upprepas på flera sidor. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Hämtar stilen för upprepande rader. |
| [get_Rows](./get_rows/)() const | Hämtar raderna i tabellen. |
| [get_Top](./get_top/)() const | Hämtar tabellens övre koordinat. |
| [GetHeight](./getheight/)(const System::SharedPtr\<Page\>\&) | Hämta höjd. |
| [GetWidth](./getwidth/)() | Hämta bredd. |
| [set_Alignment](./set_alignment/)(Aspose::Pdf::HorizontalAlignment) | Ställer in tabellens justering. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Ställer in tabellens bakgrundsfärg. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Ställer in kanten. |
| [set_BreakText](./set_breaktext/)(const System::SharedPtr\<Text::TextFragment\>\&) | Ställer in radbrytningstext för tabellen. |
| [set_Broken](./set_broken/)(TableBroken) | Ställer in tabellens vertikala avbrott;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Ställer in tabellens kolumnjustering. |
| [set_ColumnWidths](./set_columnwidths/)(const System::String\&) | Hämtar kolumnbredderna i tabellen. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Ställer in stilarna för ramens hörn. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(const System::SharedPtr\<BorderInfo\>\&) | Hämtar standardcellram;. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(const System::SharedPtr\<MarginInfo\>\&) | Ställer in standardcellens utfyllnad. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Ställer in standardtexttillståndet för cellen. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(const System::String\&) | Hämtar standardcellram;. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Ställer in att ramen inkluderas i kolumnbredderna. |
| [set_IsBroken](./set_isbroken/)(bool) | Ställer in att tabellen är bruten – den kommer att trunkeras för nästa sida. |
| [set_Left](./set_left/)(float) | Ställer in tabellens vänstra koordinat. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Ställer in maximalt antal kolumner för tabellen. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Hämtar antalet första rader som upprepas på flera sidor. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(const System::SharedPtr\<Text::TextState\>\&) | Hämtar stilen för upprepande rader. |
| [set_Top](./set_top/)(float) | Ställer in tabellens övre koordinat. |
| [SetColumnTextState](./setcolumntextstate/)(int32_t, const System::SharedPtr\<Text::TextState\>\&) | Ställ in höjd. |
| [Table](./table/)() | Standardkonstruktor. |
## Se även

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
