---
title: "Clase Aspose::Pdf::Table"
linktitle: "Tabla"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Table. Representa una tabla que puede añadirse a la página en C++."
type: docs
weight: 17700
url: /es/cpp/aspose.pdf/table/
---
## Table class


Representa una tabla que puede añadirse a la página.

```cpp
class Table : public Aspose::Pdf::BaseParagraph
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clonar la tabla. |
| [get_Alignment](./get_alignment/)() const | Obtiene la alineación de la tabla. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Obtiene el color de fondo de la tabla. |
| [get_Border](./get_border/)() const | Obtiene el borde. |
| [get_BreakText](./get_breaktext/)() const | Obtiene el texto de salto para la tabla. |
| [get_Broken](./get_broken/)() const | Obtiene table vertial broken;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Obtiene el ajuste de columna de la tabla. |
| [get_ColumnWidths](./get_columnwidths/)() const | Obtiene los anchos de columna de la tabla. |
| [get_CornerStyle](./get_cornerstyle/)() const | Obtiene los estilos de las esquinas del borde. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Obtiene el borde predeterminado de la celda;. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Obtiene el relleno predeterminado de la celda. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Obtiene el estado de texto predeterminado de la celda. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Obtiene el borde predeterminado de la celda;. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Obtiene border incluido en column widhts. |
| [get_IsBroken](./get_isbroken/)() const | Obtiene si la tabla está rota - se truncará para la página siguiente. |
| [get_Left](./get_left/)() const | Obtiene la coordenada izquierda de la tabla. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Obtiene el número máximo de columnas para la tabla. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Obtiene el recuento de primeras filas repetidas en varias páginas. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Obtiene el estilo para filas repetidas. |
| [get_Rows](./get_rows/)() const | Obtiene las filas de la tabla. |
| [get_Top](./get_top/)() const | Obtiene la coordenada superior de la tabla. |
| [GetHeight](./getheight/)(const System::SharedPtr\<Page\>\&) | Obtener altura. |
| [GetWidth](./getwidth/)() | Obtener ancho. |
| [set_Alignment](./set_alignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación de la tabla. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Establece el color de fondo de la tabla. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Establece el borde. |
| [set_BreakText](./set_breaktext/)(const System::SharedPtr\<Text::TextFragment\>\&) | Establece el texto de salto para la tabla. |
| [set_Broken](./set_broken/)(TableBroken) | Establece table vertial broken;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Establece el ajuste de columna de la tabla. |
| [set_ColumnWidths](./set_columnwidths/)(const System::String\&) | Obtiene los anchos de columna de la tabla. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Establece los estilos de las esquinas del borde. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(const System::SharedPtr\<BorderInfo\>\&) | Obtiene el borde predeterminado de la celda;. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(const System::SharedPtr\<MarginInfo\>\&) | Establece el relleno predeterminado de la celda. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Establece el estado de texto predeterminado de la celda. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(const System::String\&) | Obtiene el borde predeterminado de la celda;. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Establece el borde incluido en los anchos de columna. |
| [set_IsBroken](./set_isbroken/)(bool) | Establece que la tabla está rota - se truncará para la página siguiente. |
| [set_Left](./set_left/)(float) | Establece la coordenada izquierda de la tabla. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Establece el número máximo de columnas para la tabla. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Obtiene el recuento de primeras filas repetidas en varias páginas. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(const System::SharedPtr\<Text::TextState\>\&) | Obtiene el estilo para filas repetidas. |
| [set_Top](./set_top/)(float) | Establece la coordenada superior de la tabla. |
| [SetColumnTextState](./setcolumntextstate/)(int32_t, const System::SharedPtr\<Text::TextState\>\&) | Establecer altura. |
| [Table](./table/)() | Constructor predeterminado. |
## Ver también

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
