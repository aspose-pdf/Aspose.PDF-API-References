---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una celda de tabla que existe en la página"
type: docs
weight: 10
url: /es/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Representa una celda de tabla que existe en la página

## Métodos

| Método | Descripción |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Compara el objeto AbsorbedCell actual con otro objeto AbsorbedCell y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [getBorderInfo](#getBorderInfo--) | Devuelve la información del borde de la celda cuando la propiedad FlowEngine.TableAbsorber.UseFlowEngine está establecida en true. |
| [getColSpan](#getColSpan--) | Devuelve el número de columnas que la celda debe abarcar cuando la propiedad TableAbsorber.UseFlowEngine está establecida en true. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo que describe la posición de la celda en la página |
| [getTextFragments](#getTextFragments--) | Obtiene la colección de objetos {@code TextFragment} que describen el texto contenido en la celda |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Compara el objeto AbsorbedCell actual con otro objeto AbsorbedCell y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Devuelve la información del borde de la celda cuando la propiedad FlowEngine.TableAbsorber.UseFlowEngine está establecida en true.

**Returns:**
Instancia BorderInfo

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Devuelve el número de columnas que la celda debe abarcar cuando la propiedad TableAbsorber.UseFlowEngine está establecida en true.

**Returns:**
valor int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo que describe la posición de la celda en la página

**Returns:**
objeto Rectangle

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Obtiene la colección de objetos {@code TextFragment} que describen el texto contenido en la celda

**Returns:**
Objeto TextFragmentCollection
