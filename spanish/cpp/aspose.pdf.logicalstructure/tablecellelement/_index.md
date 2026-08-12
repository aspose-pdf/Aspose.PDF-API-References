---
title: "Aspose::Pdf::LogicalStructure::TableCellElement clase"
linktitle: "TableCellElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::TableCellElement clase. Representa una clase base para los elementos de celda de tabla (TH y TD) en la estructura lógica en C++."
type: docs
weight: 6000
url: /es/cpp/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class


Representa una clase base para los elementos de celda de tabla (TH y TD) en la estructura lógica.

```cpp
class TableCellElement : public Aspose::Pdf::LogicalStructure::TableChildElement,
                         public Aspose::Pdf::LogicalStructure::ITextElement,
                         public Aspose::Pdf::Tagged::IAdjustPosition
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Alignment](./get_alignment/)() const | Obtiene la alineación de la celda. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Obtiene el color de fondo de la celda. |
| [get_Border](./get_border/)() const | Obtiene el borde de la celda. |
| [get_ColSpan](./get_colspan/)() const | Obtiene la extensión de columna. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Obtiene el estado de texto predeterminado de la celda. |
| [get_IsNoBorder](./get_isnoborder/)() const | Obtiene si la celda tiene borde. |
| [get_IsWordWrapped](./get_iswordwrapped/)() const | Obtiene si el texto de la celda está ajustado por palabras. |
| [get_Margin](./get_margin/)() const | Obtiene el relleno. |
| [get_RowSpan](./get_rowspan/)() const | Obtiene la extensión de fila. |
| [get_StructureTextState](./get_structuretextstate/)() override | Obtiene el objeto [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) para el elemento actual. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Obtiene la alineación vertical. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Establece la alineación de la celda. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Establece el color de fondo de la celda. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Establece el borde de la celda. |
| [set_ColSpan](./set_colspan/)(int32_t) | Establece la extensión de columna. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Establece el estado de texto predeterminado de la celda. |
| [set_IsNoBorder](./set_isnoborder/)(bool) | Establece si la celda tiene borde. |
| [set_IsWordWrapped](./set_iswordwrapped/)(bool) | Establece si el texto de la celda está ajustado por palabras. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Establece el relleno. |
| [set_RowSpan](./set_rowspan/)(int32_t) | Establece la extensión de fila. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Establece la alineación vertical. |
| [SetText](./settext/)(System::String) override | Añade contenido de texto al elemento de texto actual. |
## Ver también

* Class [TableChildElement](../tablechildelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
