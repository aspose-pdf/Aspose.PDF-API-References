---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase base para los elementos de celda de tabla (TH y TD) en la estructura lógica."
type: docs
weight: 150
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Representa una clase base para los elementos de celda de tabla (TH y TD) en la estructura lógica.

## Métodos

| Método | Descripción |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posición. |
| [getAlignment](#getAlignment--) | Obtiene o establece la alineación de la celda. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene o establece el color de fondo de la celda. |
| [getBorder](#getBorder--) | Obtiene o establece el borde de la celda. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Obtiene o establece la extensión de columna. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtiene o establece el estado de texto predeterminado de la celda. |
| [getMargin](#getMargin--) | Obtiene o establece el relleno. |
| [getRowSpan](#getRowSpan--) | Obtiene o establece la extensión de fila. |
| [getStructureTextState](#getStructureTextState--) | Obtiene {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual. Valor: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene o establece la alineación vertical. |
| [isNoBorder](#isNoBorder--) | Obtiene o establece si la celda tiene borde. |
| [isWordWrapped](#isWordWrapped--) | Obtiene o establece el ajuste de palabras del texto de la celda. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtiene o establece la alineación de la celda. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtiene o establece el color de fondo de la celda. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtiene o establece el borde de la celda. |
| [setColSpan](#setColSpan-int-) | Obtiene o establece la extensión de columna. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtiene o establece el estado de texto predeterminado de la celda. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Obtiene o establece el relleno. |
| [setNoBorder](#setNoBorder-boolean-) | Obtiene o establece si la celda tiene borde. |
| [setRowSpan](#setRowSpan-int-) | Obtiene o establece la extensión de fila. |
| [setText](#setText-java.lang.String-) | Añade contenido de texto al elemento de texto actual. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtiene o establece la alineación vertical. |
| [setWordWrapped](#setWordWrapped-boolean-) | Obtiene o establece el ajuste de palabras del texto de la celda. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posición.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtiene o establece la alineación de la celda.

**Returns:**
Elemento HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtiene o establece el color de fondo de la celda.

**Returns:**
Instancia de Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtiene o establece el borde de la celda.

**Returns:**
Instancia BorderInfo

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Obtiene o establece la extensión de columna.

**Returns:**
valor int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtiene o establece el estado de texto predeterminado de la celda.

**Returns:**
instancia TextState

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Obtiene o establece el relleno.

**Returns:**
Instancia MarginInfo

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Obtiene o establece la extensión de fila.

**Returns:**
valor int

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtiene {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual. Valor: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objeto para el elemento actual.

**Returns:**
Instancia de StructureTextState

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Obtiene o establece la alineación vertical.

**Returns:**
Elemento VerticalAlignment

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Obtiene o establece si la celda tiene borde.

**Returns:**
valor booleano

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Obtiene o establece el ajuste de palabras del texto de la celda.

**Returns:**
valor booleano

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtiene o establece la alineación de la celda.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtiene o establece el color de fondo de la celda.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtiene o establece el borde de la celda.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Obtiene o establece la extensión de columna.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtiene o establece el estado de texto predeterminado de la celda.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Obtiene o establece el relleno.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Obtiene o establece si la celda tiene borde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Obtiene o establece la extensión de fila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setText {#setText-java.lang.String-}
Añade contenido de texto al elemento de texto actual.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtiene o establece la alineación vertical.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Obtiene o establece el ajuste de palabras del texto de la celda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
