---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una tabla que existe en la página"
type: docs
weight: 30
url: /es/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Representa una tabla que existe en la página

## Métodos

| Método | Descripción |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Compara el objeto AbsorbedTable actual con otro objeto AbsorbedTable y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [getPageNum](#getPageNum--) | Obtiene el número de la página que contiene esta tabla |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo que describe la posición de la tabla en la página |
| [getRowList](#getRowList--) | <p> Obtiene IList de solo lectura que contiene filas de la tabla </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Compara el objeto AbsorbedTable actual con otro objeto AbsorbedTable y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Obtiene el número de la página que contiene esta tabla

**Returns:**
valor int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo que describe la posición de la tabla en la página

**Returns:**
objeto Rectangle

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Obtiene IList de solo lectura que contiene filas de la tabla </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} objeto
