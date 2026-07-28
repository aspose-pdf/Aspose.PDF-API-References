---
title: "AbsorbedRow"
linktitle: "AbsorbedRow"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una fila de tabla que existe en la página"
type: docs
weight: 20
url: /es/java/com.aspose.pdf/absorbedrow/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedRow

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedRow >

```
public class AbsorbedRow extends Object implements ITableElement , Comparable < AbsorbedRow >
```

Representa una fila de tabla que existe en la página

## Métodos

| Método | Descripción |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedRow-) | Compara el objeto AbsorbedRow actual con otro objeto AbsorbedRow y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [getCellList](#getCellList--) | Obtiene IList de solo lectura que contiene las celdas de la fila |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo que describe la posición de la fila en la página |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedRow-}
Compara el objeto AbsorbedRow actual con otro objeto AbsorbedRow y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

### getCellList {#getCellList--}
```
public List < AbsorbedCell > getCellList()
```

Obtiene IList de solo lectura que contiene las celdas de la fila

**Returns:**
Lista de objetos AbsorbedCell

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo que describe la posición de la fila en la página

**Returns:**
Instancia de Rectangle
