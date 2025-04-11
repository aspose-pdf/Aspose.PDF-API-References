---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Table. Representa una tabla que se puede agregar a la página
type: docs
weight: 10280
url: /es/net/aspose.pdf/table/
---
## Clase Tabla

Representa una tabla que se puede agregar a la página.

```csharp
public sealed class Table : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Table](table/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Obtiene o establece la alineación de la tabla. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Obtiene o establece el color de fondo de la tabla. |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Obtiene o establece el borde. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Obtiene o establece el texto de ruptura para la tabla. |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Obtiene o establece si la tabla está rota verticalmente. |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Obtiene o establece el ajuste de columna de la tabla. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Obtiene los anchos de columna de la tabla. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Obtiene o establece los estilos de las esquinas del borde. |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Obtiene el borde de celda predeterminado. |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Obtiene o establece el relleno de celda predeterminado. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Obtiene o establece el estado de texto de celda predeterminado. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Obtiene el ancho de columna predeterminado. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del párrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Obtiene o establece si el borde está incluido en los anchos de columna. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Obtiene o establece si la tabla está rota - se truncará para la siguiente página. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que fuerza a este párrafo a generarse en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Obtiene o establece la coordenada izquierda de la tabla. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Obtiene o establece el número máximo de columnas para la tabla. |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Obtiene el número de filas que se repiten en varias páginas. |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Obtiene el estilo para las filas repetidas. |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Obtiene las filas de la tabla. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Obtiene o establece la coordenada superior de la tabla. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Clona la tabla. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Obtiene la altura. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Obtiene el ancho. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importa un array unidimensional de datos en la tabla. La importación se realiza una celda por cada elemento del array y comienza desde la fila y columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias aún están ausentes (es decir, la tabla objetivo es demasiado pequeña para absorber todos los datos), se crearán las filas necesarias. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importa datos de System.Data.DataTable en Aspose.Pdf.Table. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importa un objeto DataTable en la tabla. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importa un objeto DataTable, pero no como una entidad completa. Solo se importan las filas y columnas especificadas. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importa los datos de un objeto DataView en la tabla. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Establece la altura. |

### Ver También

* clase [BaseParagraph](../baseparagraph/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)