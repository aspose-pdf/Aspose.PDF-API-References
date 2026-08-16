---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la colección {@link GraphicElement}."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Representa la colección {@link GraphicElement}.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Inicializa la nueva colección. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Agrega un nuevo {@link GraphicElement} a la colección. Todos los elementos en la colección deben tener el mismo {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Limpia la colección. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Determina si un elemento está en la colección. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Copia toda la colección a un Array unidimensional compatible, comenzando en el índice especificado del array de destino. |
| [get_Item](#get_Item-int-) | Obtiene el elemento {@link GraphicElement} en el índice especificado. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. Siempre devuelve false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Devuelve un enumerador para toda la colección. |
| [iterator](#iterator--) | Devuelve un enumerador para toda la colección. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Elimina el elemento {@link GraphicElement}. |
| [size](#size--) | Obtiene el número de objetos {@link GraphicElement} realmente contenidos en la colección. |
| [toList](#toList--) | Devuelve la colección interna para enumeración sin restricciones. |
| [toString](#toString--) | Obtiene una representación en cadena de esta colección. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Inicializa la nueva colección.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Agrega un nuevo {@link GraphicElement} a la colección. Todos los elementos en la colección deben tener el mismo {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Limpia la colección.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Determina si un elemento está en la colección.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Copia toda la colección a un Array unidimensional compatible, comenzando en el índice especificado del array de destino.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Obtiene el elemento {@link GraphicElement} en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice dentro de la colección. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene un valor que indica si la colección es de solo lectura. Siempre devuelve false.

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Elimina el elemento {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

Obtiene el número de objetos {@link GraphicElement} realmente contenidos en la colección.

**Returns:**
valor int

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Devuelve la colección interna para enumeración sin restricciones.

**Returns:**
Lista interna

### toString {#toString--}
```
public String toString()
```

Obtiene una representación en cadena de esta colección.

**Returns:**
La cadena.
