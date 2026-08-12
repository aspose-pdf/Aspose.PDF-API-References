---
title: "Aspose::Pdf::Cell clase"
linktitle: "Cell"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Cell clase. Representa una celda de la fila de la tabla en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf/cell/
---
## Cell class


Representa una celda de la fila de la tabla.

```cpp
class Cell : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Cell](./cell/)(const System::SharedPtr\<Rectangle\>\&) | Inicializa una nueva instancia de la clase [Cell](./). |
| [Cell](./cell/)() | Inicializa una nueva instancia de la clase [Cell](./). |
| [Clone](./clone/)() override | Clona la celda. |
| [get_Alignment](./get_alignment/)() const | Obtiene la alineación. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Obtiene el color de fondo. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Obtiene la imagen de fondo. |
| [get_BackgroundImageFile](./get_backgroundimagefile/)() const | Obtiene el archivo de imagen de fondo. |
| [get_Border](./get_border/)() const | Obtiene el borde. |
| [get_ColSpan](./get_colspan/)() const | Obtiene la extensión de columna. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Obtiene el estado de texto predeterminado de la celda. |
| [get_IsNoBorder](./get_isnoborder/)() const | Obtiene si la celda tiene borde. |
| [get_IsOverrideByFragment](./get_isoverridebyfragment/)() const | Establece la propiedad TextState de la celda, la cual es sobrescrita por la propiedad TextState de TextFragment. |
| [get_IsWordWrapped](./get_iswordwrapped/)() const | Obtiene si el texto de la celda está ajustado por palabras. |
| [get_Margin](./get_margin/)() const | Obtiene el relleno. |
| [get_Paragraphs](./get_paragraphs/)() const | Obtiene el texto formateado de la celda. |
| [get_RowSpan](./get_rowspan/)() const | Obtiene la extensión de fila. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Obtiene la alineación vertical. |
| [get_Width](./get_width/)() const | Obtiene el ancho de la columna. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Establece la alineación. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Establece el color de fondo. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Image\>\&) | Establece la imagen de fondo. |
| [set_BackgroundImageFile](./set_backgroundimagefile/)(const System::String\&) | Establece el archivo de imagen de fondo. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Establece el borde. |
| [set_ColSpan](./set_colspan/)(int32_t) | Establece la extensión de columna. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Establece el estado de texto predeterminado de la celda. |
| [set_IsNoBorder](./set_isnoborder/)(bool) | Establece si la celda tiene borde. |
| [set_IsOverrideByFragment](./set_isoverridebyfragment/)(bool) | Establece la propiedad TextState de la celda, la cual es sobrescrita por la propiedad TextState de TextFragment. |
| [set_IsWordWrapped](./set_iswordwrapped/)(bool) | Establece si el texto de la celda está ajustado por palabras. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Establece el relleno. |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Establece el texto formateado de la celda. |
| [set_RowSpan](./set_rowspan/)(int32_t) | Establece la extensión de fila. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Establece la alineación vertical. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
