---
title: "Aspose::Pdf::LogicalStructure::TableCellElement-klass"
linktitle: "TableCellElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::TableCellElement-klass. Representerar en basklass för tabellcellselement (TH och TD) i den logiska strukturen i C++."
type: docs
weight: 6000
url: /sv/cpp/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class


Representerar en basklass för tabellcellselement (TH och TD) i logisk struktur.

```cpp
class TableCellElement : public Aspose::Pdf::LogicalStructure::TableChildElement,
                         public Aspose::Pdf::LogicalStructure::ITextElement,
                         public Aspose::Pdf::Tagged::IAdjustPosition
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Alignment](./get_alignment/)() const | Hämtar cellens justering. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Hämtar cellens bakgrundsfärg. |
| [get_Border](./get_border/)() const | Hämtar cellens kant. |
| [get_ColSpan](./get_colspan/)() const | Hämtar kolumnspannet. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Hämtar standardtexttillståndet för cellen. |
| [get_IsNoBorder](./get_isnoborder/)() const | Hämtar om cellen har kant. |
| [get_IsWordWrapped](./get_iswordwrapped/)() const | Hämtar om cellens text är radbryten. |
| [get_Margin](./get_margin/)() const | Hämtar utfyllnaden. |
| [get_RowSpan](./get_rowspan/)() const | Hämtar radspannet. |
| [get_StructureTextState](./get_structuretextstate/)() override | Hämtar [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) objekt för aktuellt element. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Hämtar vertikal justering. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Ställer in cellens justering. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Ställer in cellens bakgrundsfärg. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Ställer in cellens kant. |
| [set_ColSpan](./set_colspan/)(int32_t) | Ställer in kolumnspannet. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Ställer in standardtexttillståndet för cellen. |
| [set_IsNoBorder](./set_isnoborder/)(bool) | Ställer in om cellen har kant. |
| [set_IsWordWrapped](./set_iswordwrapped/)(bool) | Ställer in om cellens text är radbryten. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Sätter utfyllnaden. |
| [set_RowSpan](./set_rowspan/)(int32_t) | Ställer in radspannet. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Ställer in vertikal justering. |
| [SetText](./settext/)(System::String) override | Lägger till textinnehåll till aktuellt textelement. |
## Se även

* Class [TableChildElement](../tablechildelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
