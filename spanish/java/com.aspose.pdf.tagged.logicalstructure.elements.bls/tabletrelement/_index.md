---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el elemento de estructura TR en la estructura lógica de la tabla."
type: docs
weight: 240
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Representa el elemento de estructura TR en la estructura lógica de la tabla.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor solo para uso interno |

## Métodos

| Método | Descripción |
| --- | --- |
| [createTD](#createTD--) | Crea {@link TableTHElement} y lo agrega a la tabla actual. |
| [createTH](#createTH--) | Crea {@link TableTHElement} y lo agrega a la tabla actual. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene o establece el color de fondo de la fila. |
| [getBorder](#getBorder--) | Obtiene o establece el borde de la fila. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtiene el borde predeterminado de la celda. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtiene o establece el margen predeterminado para las celdas de la fila. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtiene o establece el estado de texto predeterminado para las celdas de la fila |
| [getFixedRowHeight](#getFixedRowHeight--) | Obtiene la altura fija de la fila - la fila puede tener una altura fija. |
| [getMinRowHeight](#getMinRowHeight--) | Obtiene la altura de la fila. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene o establece la alineación vertical. |
| [isInNewPage](#isInNewPage--) | Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la página siguiente. Valor predeterminado false. |
| [isRowBroken](#isRowBroken--) | Obtiene si la fila puede dividirse entre dos páginas. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtiene o establece el color de fondo de la fila. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtiene o establece el borde de la fila. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtiene el borde predeterminado de la celda. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Obtiene o establece el margen predeterminado para las celdas de la fila. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtiene o establece el estado de texto predeterminado para las celdas de la fila |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Obtiene la altura fija de la fila - la fila puede tener una altura fija. |
| [setInNewPage](#setInNewPage-boolean-) | Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la página siguiente. Valor predeterminado false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Obtiene la altura de la fila. |
| [setRowBroken](#setRowBroken-boolean-) | Obtiene si la fila puede dividirse entre dos páginas. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtiene o establece la alineación vertical. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
constructor solo para uso interno

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Crea {@link TableTHElement} y lo agrega a la tabla actual.

**Returns:**
Elemento de estructura creado.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Crea {@link TableTHElement} y lo agrega a la tabla actual.

**Returns:**
Elemento de estructura creado.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtiene o establece el color de fondo de la fila.

**Returns:**
Instancia de Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtiene o establece el borde de la fila.

**Returns:**
Instancia BorderInfo

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

Obtiene o establece el margen predeterminado para las celdas de la fila.

**Returns:**
Instancia MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtiene o establece el estado de texto predeterminado para las celdas de la fila

**Returns:**
instancia TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Obtiene la altura fija de la fila - la fila puede tener una altura fija.

**Returns:**
valor double

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Obtiene la altura de la fila.

**Returns:**
valor double

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Obtiene o establece la alineación vertical.

**Returns:**
Elemento VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la página siguiente. Valor predeterminado false.

**Returns:**
valor booleano

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Obtiene si la fila puede dividirse entre dos páginas.

**Returns:**
valor booleano

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtiene o establece el color de fondo de la fila.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtiene o establece el borde de la fila.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtiene el borde predeterminado de la celda.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Obtiene o establece el margen predeterminado para las celdas de la fila.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtiene o establece el estado de texto predeterminado para las celdas de la fila

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Obtiene la altura fija de la fila - la fila puede tener una altura fija.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la página siguiente. Valor predeterminado false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Obtiene la altura de la fila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Obtiene si la fila puede dividirse entre dos páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtiene o establece la alineación vertical.
