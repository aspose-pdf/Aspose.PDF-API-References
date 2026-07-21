---
title: "Clase Aspose::Pdf::LogicalStructure::TableElement"
linktitle: "TableElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LogicalStructure::TableElement. Representa el elemento de estructura Table en la estructura lógica en C++."
type: docs
weight: 6200
url: /es/cpp/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class


Representa el elemento de estructura [Table](../../aspose.pdf/table/) en la estructura lógica.

```cpp
class TableElement : public Aspose::Pdf::LogicalStructure::BLSElement,
                     public Aspose::Pdf::Tagged::IAdjustPosition
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [CreateTBody](./createtbody/)() | Crea [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) y lo agrega a la tabla actual. |
| [CreateTFoot](./createtfoot/)() | Crea [Aspose::Pdf::LogicalStructure::TableTFootElement](../tabletfootelement/) y lo agrega a la tabla actual. |
| [CreateTHead](./createthead/)() | Crea [Aspose::Pdf::LogicalStructure::TableTHeadElement](../tabletheadelement/) y lo agrega a la tabla actual. |
| [get_Alignment](./get_alignment/)() const | Obtiene la alineación de la tabla. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Obtiene el color de fondo de la tabla. |
| [get_Border](./get_border/)() const | Obtiene el borde de la tabla. |
| [get_Broken](./get_broken/)() const | Obtiene table vertial broken;. |
| [get_ColumnAdjustment](./get_columnadjustment/)() const | Obtiene el ajuste de columna de la tabla. |
| [get_ColumnWidths](./get_columnwidths/)() const | Obtiene los anchos de columna de la tabla. |
| [get_CornerStyle](./get_cornerstyle/)() const | Obtiene los estilos de las esquinas del borde. |
| [get_DefaultCellBorder](./get_defaultcellborder/)() const | Obtiene el borde predeterminado de la celda. |
| [get_DefaultCellPadding](./get_defaultcellpadding/)() const | Obtiene el relleno predeterminado de la celda. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Obtiene el estado de texto predeterminado de la celda. |
| [get_DefaultColumnWidth](./get_defaultcolumnwidth/)() const | Obtiene el ancho predeterminado de la columna. |
| [get_IsBordersIncluded](./get_isbordersincluded/)() const | Obtiene border incluido en column widhts. |
| [get_IsBroken](./get_isbroken/)() const | Obtiene si la tabla está rota - se truncará para la página siguiente. |
| [get_Left](./get_left/)() const | Obtiene la coordenada izquierda de la tabla. |
| [get_RepeatingColumnsCount](./get_repeatingcolumnscount/)() const | Obtiene el número máximo de columnas para la tabla. |
| [get_RepeatingRowsCount](./get_repeatingrowscount/)() const | Obtiene el recuento de primeras filas repetidas en varias páginas. |
| [get_RepeatingRowsStyle](./get_repeatingrowsstyle/)() const | Obtiene el estilo para filas repetidas. |
| [get_Top](./get_top/)() const | Obtiene la coordenada superior de la tabla. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Establece la alineación de la tabla. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Establece el color de fondo de la tabla. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Establece el borde de la tabla. |
| [set_Broken](./set_broken/)(TableBroken) | Establece table vertial broken;. |
| [set_ColumnAdjustment](./set_columnadjustment/)(Aspose::Pdf::ColumnAdjustment) | Establece el ajuste de columna de la tabla. |
| [set_ColumnWidths](./set_columnwidths/)(const System::String\&) | Obtiene los anchos de columna de la tabla. |
| [set_CornerStyle](./set_cornerstyle/)(BorderCornerStyle) | Establece los estilos de las esquinas del borde. |
| [set_DefaultCellBorder](./set_defaultcellborder/)(const System::SharedPtr\<BorderInfo\>\&) | Obtiene el borde predeterminado de la celda. |
| [set_DefaultCellPadding](./set_defaultcellpadding/)(const System::SharedPtr\<MarginInfo\>\&) | Establece el relleno predeterminado de la celda. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Establece el estado de texto predeterminado de la celda. |
| [set_DefaultColumnWidth](./set_defaultcolumnwidth/)(const System::String\&) | Establece el ancho de columna predeterminado. |
| [set_IsBordersIncluded](./set_isbordersincluded/)(bool) | Establece el borde incluido en los anchos de columna. |
| [set_IsBroken](./set_isbroken/)(bool) | Establece que la tabla está rota - se truncará para la página siguiente. |
| [set_Left](./set_left/)(float) | Establece la coordenada izquierda de la tabla. |
| [set_RepeatingColumnsCount](./set_repeatingcolumnscount/)(int32_t) | Establece el número máximo de columnas para la tabla. |
| [set_RepeatingRowsCount](./set_repeatingrowscount/)(int32_t) | Obtiene el recuento de primeras filas repetidas en varias páginas. |
| [set_RepeatingRowsStyle](./set_repeatingrowsstyle/)(const System::SharedPtr\<Text::TextState\>\&) | Obtiene el estilo para filas repetidas. |
| [set_Top](./set_top/)(float) | Establece la coordenada superior de la tabla. |
## Ver también

* Class [BLSElement](../blselement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
