---
title: "Tabla"
linktitle: "Tabla"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una tabla que se puede agregar a la página."
type: docs
weight: 4790
url: /es/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Representa una tabla que se puede agregar a la página.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Table](#Table--) | ctor predeterminado |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Importa una matriz unidimensional de datos en la tabla. La importación coloca una celda por cada elemento de la matriz y / * comienza desde la fila y columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias / * aún están ausentes (es decir, la tabla objetivo es demasiado pequeña para absorber todos los datos), se crearán las filas necesarias / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Agregar operadores para rectángulo. |
| [getAlignment](#getAlignment--) | Obtiene la alineación de la tabla. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene el color de fondo de la tabla |
| [getBorder](#getBorder--) | Obtiene el borde. |
| [getBreakText](#getBreakText--) | Obtiene el texto de salto para la tabla |
| [getBroken](#getBroken--) | Obtiene o establece la ruptura vertical de la tabla; |
| [getColumnAdjustment](#getColumnAdjustment--) | Obtiene el ajuste de columna de la tabla. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Obtener ancho de columna |
| [getColumnWidths](#getColumnWidths--) | Obtiene los anchos de columna de la tabla. |
| [getCornerStyle](#getCornerStyle--) | Obtiene los estilos de las esquinas del borde |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtiene el borde predeterminado de la celda; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtiene el relleno predeterminado de la celda. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtiene el estado de texto predeterminado de la celda. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Obtiene el borde predeterminado de la celda; |
| [getHeight](#getHeight--) | Obtener altura. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Obtener altura. |
| [getLeft](#getLeft--) | Obtiene la coordenada izquierda de la tabla. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Obtiene o establece el número máximo de columnas para la tabla |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Obtiene el recuento de filas iniciales repetidas en varias páginas |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Obtiene el estilo para filas repetidas |
| [getRows](#getRows--) | Obtiene las filas de la tabla. |
| [getTop](#getTop--) | Obtiene la coordenada superior de la tabla. |
| [getWidth](#getWidth--) | Obtener ancho. |
| [isBordersIncluded](#isBordersIncluded--) | Obtiene el borde incluido en los anchos de columna. |
| [isBroken](#isBroken--) | Obtiene que la tabla está rota - se truncará para la página siguiente. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación de la tabla. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Establece el color de fondo de la tabla |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Establece el borde. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Establece el borde incluido en los anchos de columna. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Establece el texto de salto para la tabla |
| [setBroken](#setBroken-boolean-) | Establece que la tabla está rota - se truncará para la página siguiente. |
| [setBroken](#setBroken-int-) | Obtiene o establece la ruptura vertical de la tabla; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Establece el ajuste de columna de la tabla. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Establece la altura. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Obtiene los anchos de columna de la tabla. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Obtiene o establece los estilos de las esquinas del borde |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtiene el borde predeterminado de la celda; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Establece el relleno predeterminado de la celda. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Establece el estado de texto predeterminado de la celda. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Obtiene el borde predeterminado de la celda; |
| [setLeft](#setLeft-float-) | Establece la coordenada izquierda de la tabla. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Obtiene o establece el número máximo de columnas para la tabla |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Obtiene el recuento de filas iniciales repetidas en varias páginas |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Obtiene el estilo para filas repetidas |
| [setTop](#setTop-float-) | Establece la coordenada superior de la tabla. |

### Table {#Table--}
```
public Table()
```

ctor predeterminado

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Importa una matriz unidimensional de datos en la tabla. La importación coloca una celda por cada elemento de la matriz y / * comienza desde la fila y columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias / * aún están ausentes (es decir, la tabla objetivo es demasiado pequeña para absorber todos los datos), se crearán las filas necesarias / * / *

**Returns:**
El objeto clonado

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Agregar operadores para rectángulo.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtiene la alineación de la tabla.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtiene el color de fondo de la tabla

**Returns:**
Objeto Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtiene el borde.

**Returns:**
Objeto BorderInfo

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Obtiene el texto de salto para la tabla

**Returns:**
Objeto TextFragment

### getBroken {#getBroken--}
```
public final int getBroken()
```

Obtiene o establece la ruptura vertical de la tabla;

**Returns:**
Valor TableBroken @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Obtiene el ajuste de columna de la tabla.

**Returns:**
Valor ColumnAdjustment @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Obtener ancho de columna

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Obtiene los anchos de columna de la tabla.

**Returns:**
valor String

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Obtiene los estilos de las esquinas del borde

**Returns:**
Valor BorderCornerStyle @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Obtiene el borde predeterminado de la celda;

**Returns:**
Objeto BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Obtiene el relleno predeterminado de la celda.

**Returns:**
Objeto MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtiene el estado de texto predeterminado de la celda.

**Returns:**
Valor TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Obtiene el borde predeterminado de la celda;

**Returns:**
Objeto String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtener altura.

**Returns:**
La altura de la tabla

### getHeight {#getHeight-com.aspose.pdf.Page-}
Obtener altura.

**Returns:**
La altura de la tabla

### getLeft {#getLeft--}
```
public final float getLeft()
```

Obtiene la coordenada izquierda de la tabla.

**Returns:**
valor flotante

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Obtiene o establece el número máximo de columnas para la tabla

**Returns:**
valor int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Obtiene el recuento de filas iniciales repetidas en varias páginas

**Returns:**
valor int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Obtiene el estilo para filas repetidas

**Returns:**
Objeto TextState

### getRows {#getRows--}
```
public final Rows getRows()
```

Obtiene las filas de la tabla.

**Returns:**
Objeto Rows

### getTop {#getTop--}
```
public final float getTop()
```

Obtiene la coordenada superior de la tabla.

**Returns:**
valor flotante

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtener ancho.

**Returns:**
El ancho de la tabla

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Obtiene el borde incluido en los anchos de columna.

**Returns:**
valor booleano

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Obtiene que la tabla está rota - se truncará para la página siguiente.

**Returns:**
valor booleano

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación de la tabla.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Establece el color de fondo de la tabla

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Establece el borde.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Establece el borde incluido en los anchos de columna.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Establece el texto de salto para la tabla

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Establece que la tabla está rota - se truncará para la página siguiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Obtiene o establece la ruptura vertical de la tabla;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor TableBroken @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Establece el ajuste de columna de la tabla.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Establece la altura.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Obtiene los anchos de columna de la tabla.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Obtiene o establece los estilos de las esquinas del borde

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtiene el borde predeterminado de la celda;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Establece el relleno predeterminado de la celda.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Establece el estado de texto predeterminado de la celda.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Obtiene el borde predeterminado de la celda;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Establece la coordenada izquierda de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Obtiene o establece el número máximo de columnas para la tabla

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Obtiene el recuento de filas iniciales repetidas en varias páginas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Obtiene el estilo para filas repetidas

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Establece la coordenada superior de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |
