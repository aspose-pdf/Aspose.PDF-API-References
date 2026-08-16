---
title: "Row"
linktitle: "Row"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una fila de la tabla."
type: docs
weight: 4330
url: /es/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

Representa una fila de la tabla.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Row](#Row--) | Inicializa una nueva instancia de la clase Row. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clonar la fila. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene el color de fondo. |
| [getBorder](#getBorder--) | Obtiene el borde. |
| [getCells](#getCells--) | Obtiene el getCells() de la fila. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtiene el borde predeterminado de la celda; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtiene el margen predeterminado para la fila getCells(). |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtiene o establece el estado de texto predeterminado para la fila getCells() Obtiene el estado de texto predeterminado para la fila getCells(). |
| [getFixedRowHeight](#getFixedRowHeight--) | Obtiene la altura fija de la fila - la fila puede tener altura fija; |
| [getMinRowHeight](#getMinRowHeight--) | Obtiene la altura de la fila; |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene o establece la alineación vertical. |
| [isInNewPage](#isInNewPage--) | Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la página siguiente. Valor predeterminado false; |
| [isRowBroken](#isRowBroken--) | Obtiene si la fila puede dividirse entre dos páginas |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Establece el color de fondo. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Establece el borde. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | Establece el getCells() de la fila. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Establece el borde predeterminado de la celda; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Establece el margen predeterminado para la fila getCells() |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Establece el estado de texto predeterminado para la fila getCells() |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Establece la altura fija de la fila - la fila puede tener altura fija; |
| [setInNewPage](#setInNewPage-boolean-) | Establece si la fila puede dividirse entre dos páginas |
| [setMinRowHeight](#setMinRowHeight-double-) | Establece la altura de la fila; |
| [setRowBroken](#setRowBroken-boolean-) | Establece si la fila puede dividirse entre dos páginas |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtiene o establece la alineación vertical. |

### Row {#Row--}
```
public Row()
```

Inicializa una nueva instancia de la clase Row.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clonar la fila.

**Returns:**
El objeto clonado

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtiene el color de fondo.

**Returns:**
Valor de color

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtiene el borde.

**Returns:**
Valor de BorderInfo

### getCells {#getCells--}
```
public Cells getCells()
```

Obtiene el getCells() de la fila.

**Returns:**
Valor de getCells()

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

Obtiene el borde predeterminado de la celda;

**Returns:**
Valor de BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

Obtiene el margen predeterminado para la fila getCells().

**Returns:**
valor MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Obtiene o establece el estado de texto predeterminado para la fila getCells() Obtiene el estado de texto predeterminado para la fila getCells().

**Returns:**
Valor TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

Obtiene la altura fija de la fila - la fila puede tener altura fija;

**Returns:**
valor double

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

Obtiene la altura de la fila;

**Returns:**
valor double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtiene o establece la alineación vertical.

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la página siguiente. Valor predeterminado false;

**Returns:**
valor booleano

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

Obtiene si la fila puede dividirse entre dos páginas

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Establece el color de fondo.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Establece el borde.

### setCells {#setCells-com.aspose.pdf.Cells-}
Establece el getCells() de la fila.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Establece el borde predeterminado de la celda;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Establece el margen predeterminado para la fila getCells()

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Establece el estado de texto predeterminado para la fila getCells()

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

Establece la altura fija de la fila - la fila puede tener altura fija;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Establece si la fila puede dividirse entre dos páginas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

Establece la altura de la fila;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

Establece si la fila puede dividirse entre dos páginas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtiene o establece la alineación vertical.
