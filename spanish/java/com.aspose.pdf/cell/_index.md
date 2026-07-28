---
title: "Cell"
linktitle: "Cell"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una celda de la fila de la tabla."
type: docs
weight: 510
url: /es/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Representa una celda de la fila de la tabla.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Cell](#Cell--) | Inicializa una nueva instancia de la clase Cell. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia de la clase Cell. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona la celda. |
| [getAlignment](#getAlignment--) | Obtiene la alineación. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene el color de fondo. |
| [getBackgroundImage](#getBackgroundImage--) | Obtiene o establece la imagen de fondo |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Obtiene el archivo de imagen de fondo. |
| [getBorder](#getBorder--) | Obtiene el borde. |
| [getColSpan](#getColSpan--) | Obtiene o establece la extensión de columna. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtiene el estado de texto predeterminado de la celda. |
| [getMargin](#getMargin--) | Obtiene el relleno. |
| [getParagraphs](#getParagraphs--) | Obtiene el texto formateado de la celda. |
| [getRowSpan](#getRowSpan--) | Obtiene la extensión de fila. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene la alineación vertical. |
| [getWidth](#getWidth--) | Obtiene el ancho de columna. |
| [isNoBorder](#isNoBorder--) | Obtiene si la celda tiene borde. |
| [isOverrideByFragment](#isOverrideByFragment--) | Establece la propiedad TextState de la celda es sobrescrita por la propiedad TextState de TextFragment. |
| [isWordWrapped](#isWordWrapped--) | Obtiene el ajuste de palabras del texto de la celda. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtiene o establece el color de fondo. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtiene o establece la imagen de fondo |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Establece el archivo de imagen de fondo. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Establece el borde. |
| [setColSpan](#setColSpan-int-) | Establece la extensión de columna. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Establece el estado de texto predeterminado de la celda. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Establece el relleno. |
| [setNoBorder](#setNoBorder-boolean-) | Establece si la celda tiene borde. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Establece la propiedad TextState de la celda es sobrescrita por la propiedad TextState de TextFragment. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Establece el texto formateado de la celda. |
| [setRowSpan](#setRowSpan-int-) | Establece la extensión de fila. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece la alineación vertical. |
| [setWidth](#setWidth-double-) | Establece el ancho de columna. |
| [setWordWrapped](#setWordWrapped-boolean-) | Establece el ajuste de palabras del texto de la celda. |

### Cell {#Cell--}
```
public Cell()
```

Inicializa una nueva instancia de la clase Cell.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia de la clase Cell.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona la celda.

**Returns:**
El objeto clonado

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Obtiene la alineación.

**Returns:**
HorizontalAlignment elemento @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtiene el color de fondo.

**Returns:**
Objeto Color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtiene o establece la imagen de fondo

**Returns:**
Instancia de imagen

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Obtiene el archivo de imagen de fondo.

**Returns:**
Valor de cadena @deprecated La propiedad fue ampliada, por favor use BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtiene el borde.

**Returns:**
Objeto BorderInfo

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Obtiene o establece la extensión de columna.

**Returns:**
valor int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Obtiene el estado de texto predeterminado de la celda.

**Returns:**
Objeto TextState

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtiene el relleno.

**Returns:**
Objeto MarginInfo

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtiene el texto formateado de la celda.

**Returns:**
Objeto Paragraphs

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Obtiene la extensión de fila.

**Returns:**
valor int

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtiene la alineación vertical.

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho de columna.

**Returns:**
valor double

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Obtiene si la celda tiene borde.

**Returns:**
valor booleano

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Establece la propiedad TextState de la celda es sobrescrita por la propiedad TextState de TextFragment.

**Returns:**
valor booleano

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Obtiene el ajuste de palabras del texto de la celda.

**Returns:**
valor booleano

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtiene o establece el color de fondo.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtiene o establece la imagen de fondo

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Establece el archivo de imagen de fondo.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Establece el borde.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Establece la extensión de columna.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Establece el estado de texto predeterminado de la celda.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Establece el relleno.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Establece si la celda tiene borde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Establece la propiedad TextState de la celda es sobrescrita por la propiedad TextState de TextFragment.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Establece el texto formateado de la celda.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Establece la extensión de fila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece la alineación vertical.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece el ancho de columna.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Establece el ajuste de palabras del texto de la celda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
