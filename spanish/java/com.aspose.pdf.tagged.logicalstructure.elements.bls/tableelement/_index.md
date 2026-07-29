---
title: "TableElement"
linktitle: "TableElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el elemento estructural Table en la estructura lógica."
type: docs
weight: 170
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Representa el elemento estructural Table en la estructura lógica.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor solo para uso interno |

## Métodos

| Método | Descripción |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posición. |
| [createTBody](#createTBody--) | Crea {@link TableTHeadElement} y lo agrega a la tabla actual. |
| [createTFoot](#createTFoot--) | Crea {@link TableTFootElement} y lo agrega a la tabla actual. |
| [createTHead](#createTHead--) | Crea {@link TableTHeadElement} y lo agrega a la tabla actual. |
| [getAlignment](#getAlignment--) | Obtiene o establece la alineación de la tabla. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene o establece el color de fondo de la tabla. |
| [getBorder](#getBorder--) | Obtiene o establece el borde de la tabla. |
| [getBroken](#getBroken--) | Obtiene o establece la ruptura vertical de la tabla; |
| [getColumnAdjustment](#getColumnAdjustment--) | Obtiene o establece el ajuste de columna de la tabla. |
| [getColumnWidths](#getColumnWidths--) | Obtiene los anchos de columna de la tabla. |
| [getCornerStyle](#getCornerStyle--) | Obtiene o establece los estilos de las esquinas del borde |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtiene el borde predeterminado de la celda. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtiene o establece el relleno predeterminado de la celda. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtiene o establece el estado de texto predeterminado de la celda. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Obtiene o establece el ancho predeterminado de la columna. |
| [getLeft](#getLeft--) | Obtiene o establece la coordenada izquierda de la tabla. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Obtiene o establece el número máximo de columnas para la tabla. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Obtiene el recuento de filas iniciales que se repite en varias páginas. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Obtiene el estilo para filas repetidas. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Obtiene o establece la coordenada superior de la tabla. |
| [isBordersIncluded](#isBordersIncluded--) | Obtiene o establece el borde incluido en los anchos de columna. |
| [isBroken](#isBroken--) | Obtiene o establece si la tabla está rota - se truncará en la página siguiente. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtiene o establece la alineación de la tabla. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtiene o establece el color de fondo de la tabla. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtiene o establece el borde de la tabla. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Obtiene o establece el borde incluido en los anchos de columna. |
| [setBroken](#setBroken-boolean-) | Obtiene o establece si la tabla está rota - se truncará en la página siguiente. |
| [setBroken](#setBroken-int-) | Obtiene o establece la ruptura vertical de la tabla; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Obtiene o establece el ajuste de columna de la tabla. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Obtiene los anchos de columna de la tabla. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Obtiene o establece los estilos de las esquinas del borde |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtiene el borde predeterminado de la celda. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Obtiene o establece el relleno predeterminado de la celda. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtiene o establece el estado de texto predeterminado de la celda. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Obtiene o establece el ancho predeterminado de la columna. |
| [setLeft](#setLeft-float-) | Obtiene o establece la coordenada izquierda de la tabla. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Obtiene o establece el número máximo de columnas para la tabla. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Obtiene el recuento de filas iniciales que se repite en varias páginas. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Obtiene el estilo para filas repetidas. |
| [setTop](#setTop-float-) | Obtiene o establece la coordenada superior de la tabla. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
constructor solo para uso interno

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posición.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Crea {@link TableTHeadElement} y lo agrega a la tabla actual.

**Returns:**
Elemento de estructura creado.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Crea {@link TableTFootElement} y lo agrega a la tabla actual.

**Returns:**
Elemento de estructura creado.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Crea {@link TableTHeadElement} y lo agrega a la tabla actual.

**Returns:**
Elemento de estructura creado.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtiene o establece la alineación de la tabla.

**Returns:**
Elemento HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtiene o establece el color de fondo de la tabla.

**Returns:**
Instancia de Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtiene o establece el borde de la tabla.

**Returns:**
Instancia BorderInfo

### getBroken {#getBroken--}
```
public final int getBroken()
```

Obtiene o establece la ruptura vertical de la tabla;

**Returns:**
Elemento TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Obtiene o establece el ajuste de columna de la tabla.

**Returns:**
ColumnAdjustment elemento

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

Obtiene o establece los estilos de las esquinas del borde

**Returns:**
BorderCornerStyle elemento

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Obtiene el borde predeterminado de la celda.

**Returns:**
Instancia BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Obtiene o establece el relleno predeterminado de la celda.

**Returns:**
Instancia MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtiene o establece el estado de texto predeterminado de la celda.

**Returns:**
instancia TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Obtiene o establece el ancho predeterminado de la columna.

**Returns:**
valor String

### getLeft {#getLeft--}
```
public final float getLeft()
```

Obtiene o establece la coordenada izquierda de la tabla.

**Returns:**
valor flotante

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Obtiene o establece el número máximo de columnas para la tabla.

**Returns:**
valor int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Obtiene el recuento de filas iniciales que se repite en varias páginas.

**Returns:**
valor int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Obtiene el estilo para filas repetidas.

**Returns:**
instancia TextState

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Obtiene o establece la coordenada superior de la tabla.

**Returns:**
valor flotante

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Obtiene o establece el borde incluido en los anchos de columna.

**Returns:**
valor booleano

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Obtiene o establece si la tabla está rota - se truncará en la página siguiente.

**Returns:**
valor booleano

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtiene o establece la alineación de la tabla.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtiene o establece el color de fondo de la tabla.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtiene o establece el borde de la tabla.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Obtiene o establece el borde incluido en los anchos de columna.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Obtiene o establece si la tabla está rota - se truncará en la página siguiente.

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
| valor |  | Elemento TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Obtiene o establece el ajuste de columna de la tabla.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Obtiene los anchos de columna de la tabla.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Obtiene o establece los estilos de las esquinas del borde

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtiene el borde predeterminado de la celda.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Obtiene o establece el relleno predeterminado de la celda.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtiene o establece el estado de texto predeterminado de la celda.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Obtiene o establece el ancho predeterminado de la columna.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Obtiene o establece la coordenada izquierda de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Obtiene o establece el número máximo de columnas para la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Obtiene el recuento de filas iniciales que se repite en varias páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Obtiene el estilo para filas repetidas.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Obtiene o establece la coordenada superior de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |
