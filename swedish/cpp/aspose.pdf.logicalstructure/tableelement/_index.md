---
title: "Aspose::Pdf::LogicalStructure::TableElement klass"
linktitle: "TableElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::TableElement-klass. Representerar Table-strukturelement i den logiska strukturen i C++."
type: docs
weight: 6200
url: /sv/cpp/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class


Representerar [Table](../../aspose.pdf/table/) strukturelement i den logiska strukturen.

```cpp
class TableElement : public Aspose::Pdf::LogicalStructure::BLSElement,
                     public Aspose::Pdf::Tagged::IAdjustPosition
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [CreateTBody](./createtbody/)() | Skapar [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) och lägger till den i den aktuella tabellen. |
| [CreateTFoot](./createtfoot/)() | Skapar [Aspose::Pdf::LogicalStructure::TableTFootElement](../tabletfootelement/) och lägger till den i den aktuella tabellen. |
| [CreateTHead](./createthead/)() | Skapar [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) och lägger till den i den aktuella tabellen. |
| [get_Alignment](./get_alignment/)() const | Hämtar tabellens justering. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Hämtar tabellens bakgrundsfärg. |
| [get_Border](./get_border/)() const | Hämtar tabellens kant. |
| [get_Broken](./get_broken/)() const | Hämtar tabellens vertikala avbrott;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Hämtar tabellens kolumnjustering. |
| [get_ColumnWidths](./get_columnwidths/)() const | Hämtar kolumnbredderna i tabellen. |
| [get_CornerStyle](./get_cornerstyle/)() const | Hämtar stilarna för kantens hörn. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Hämtar standardcellens kant. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Hämtar standardcellens fyllnad. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Hämtar standardtexttillståndet för cellen. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Hämtar standardkolumnbredd. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Hämtar kant inkluderad i kolumnbredder. |
| [get_IsBroken](./get_isbroken/)() const | Hämtar om tabellen är avbruten – kommer att trunkeras för nästa sida. |
| [get_Left](./get_left/)() const | Hämtar tabellens vänstra koordinat. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Hämtar maximalt antal kolumner för tabellen. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Hämtar antalet första rader som upprepas på flera sidor. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Hämtar stilen för upprepande rader. |
| [get_Top](./get_top/)() const | Hämtar tabellens övre koordinat. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Ställer in tabellens justering. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Ställer in tabellens bakgrundsfärg. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Ställer in tabellens kant. |
| [set_Broken](./set_broken/)(TableBroken) | Ställer in tabellens vertikala avbrott;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Ställer in tabellens kolumnjustering. |
| [set_ColumnWidths](./set_columnwidths/)(const System::String\&) | Hämtar kolumnbredderna i tabellen. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Ställer in stilarna för ramens hörn. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(const System::SharedPtr\<BorderInfo\>\&) | Hämtar standardcellens kant. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(const System::SharedPtr\<MarginInfo\>\&) | Ställer in standardcellens utfyllnad. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Ställer in standardtexttillståndet för cellen. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(const System::String\&) | Ställer in standardkolumnbredd. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Ställer in att ramen inkluderas i kolumnbredderna. |
| [set_IsBroken](./set_isbroken/)(bool) | Ställer in att tabellen är bruten – den kommer att trunkeras för nästa sida. |
| [set_Left](./set_left/)(float) | Ställer in tabellens vänstra koordinat. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Ställer in maximalt antal kolumner för tabellen. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Hämtar antalet första rader som upprepas på flera sidor. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(const System::SharedPtr\<Text::TextState\>\&) | Hämtar stilen för upprepande rader. |
| [set_Top](./set_top/)(float) | Ställer in tabellens övre koordinat. |
## Se även

* Class [BLSElement](../blselement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
