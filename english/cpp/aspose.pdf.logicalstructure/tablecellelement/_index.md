---
title: Aspose::Pdf::LogicalStructure::TableCellElement class
linktitle: TableCellElement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::TableCellElement class. Represents a base class for table cell elements (TH and TD) in logical structure in C++.'
type: docs
weight: 6000
url: /cpp/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class


Represents a base class for table cell elements (TH and TD) in logical structure.

```cpp
class TableCellElement : public Aspose::Pdf::LogicalStructure::TableChildElement,
                         public Aspose::Pdf::LogicalStructure::ITextElement,
                         public Aspose::Pdf::Tagged::IAdjustPosition
```

## Methods

| Method | Description |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Alignment](./get_alignment/)() const | Gets the cell alignment. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets the cell background color. |
| [get_Border](./get_border/)() const | Gets the cell border. |
| [get_ColSpan](./get_colspan/)() const | Gets the column span. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Gets the default cell text state. |
| [get_IsNoBorder](./get_isnoborder/)() const | Gets the cell have border. |
| [get_IsWordWrapped](./get_iswordwrapped/)() const | Gets the cell's text word wrapped. |
| [get_Margin](./get_margin/)() const | Gets the padding. |
| [get_RowSpan](./get_rowspan/)() const | Gets the row span. |
| [get_StructureTextState](./get_structuretextstate/)() override | Gets [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) object for current element. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Gets the vertical alignment. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Sets the cell alignment. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets the cell background color. |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets the cell border. |
| [set_ColSpan](./set_colspan/)(int32_t) | Sets the column span. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(System::SharedPtr\<Text::TextState\>) | Sets the default cell text state. |
| [set_IsNoBorder](./set_isnoborder/)(bool) | Sets the cell have border. |
| [set_IsWordWrapped](./set_iswordwrapped/)(bool) | Sets the cell's text word wrapped. |
| [set_Margin](./set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets the padding. |
| [set_RowSpan](./set_rowspan/)(int32_t) | Sets the row span. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets the vertical alignment. |
| [SetText](./settext/)(System::String) override | Appends text content to current text element. |
## See Also

* Class [TableChildElement](../tablechildelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
