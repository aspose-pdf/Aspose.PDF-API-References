---
title: Table
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una tabla que se puede agregar a la página.
type: docs
weight: 6500
url: /es/net/aspose.pdf/table/
---
## Table class

Representa una tabla que se puede agregar a la página.

```csharp
public sealed class Table : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Table](table)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Obtiene o establece la alineación de la tabla. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo de la tabla |
| [Border](../../aspose.pdf/table/border) { get; set; } | Obtiene o establece el borde. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | Obtiene o establece el texto de ruptura para table |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Obtiene o establece la tabla vertical rota; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Obtiene o establece el ajuste de la columna de la tabla. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Obtiene los anchos de columna de la tabla. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Obtiene o establece los estilos de las esquinas del borde |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Obtiene el borde de celda predeterminado; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Obtiene o establece el relleno de celda predeterminado. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Obtiene o establece el estado de texto de celda predeterminado. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Obtiene el borde de celda predeterminado; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Obtiene o establece una alineación horizontal del párrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Obtiene o establece el borde incluido en los anchos de columna. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Obtiene o establece que la tabla está rota: se truncará para la página siguiente. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtiene o establece que un párrafo está en línea. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtiene o establece un valor booleano que obliga a generar este párrafo en una nueva página. El valor predeterminado es falso. (para la generación de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el párrafo siguiente. El valor predeterminado es falso. (para la generación de PDF) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Obtiene o establece la coordenada izquierda de la tabla. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | Obtiene o establece el recuento máximo de columnas para table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Obtiene el recuento de las primeras filas repetido para varias páginas |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Obtiene el estilo para repetir filas |
| [Rows](../../aspose.pdf/table/rows) { get; } | Obtiene las filas de la tabla. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Obtiene o establece la coordenada superior de la mesa. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Clonar la tabla. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Obtener altura. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Obtener ancho. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Importa una matriz unidimensional de datos en la tabla. La importación va una celda por elemento de cada matriz y comienza desde la fila y la columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias todavía están ausentes (es decir, la tabla de destino es demasiado pequeña para absorber todos los datos), se crearán las filas necesarias |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | Importa datos de System.Data.DataTable a Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importa unDataTable objeto en la tabla. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importa unDataTable objeto, pero no como entidad completa. Solo se importan las filas y columnas especificadas. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | Importa unDataView datos del objeto en la tabla. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Establecer altura. |

### Ver también

* class [BaseParagraph](../baseparagraph)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
