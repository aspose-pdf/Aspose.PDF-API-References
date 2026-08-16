---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una colección de segmentos de texto"
type: docs
weight: 5310
url: /es/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

Representa una colección de segmentos de texto

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | Agrega el elemento de segmento de texto en el índice especificado. |
| [clear](#clear--) | Elimina todos los elementos de la colección. |
| [contains](#contains-com.aspose.pdf.TextSegment-) | Determina si la colección contiene un valor específico. |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [delete](#delete-int-) | Elimina el elemento de segmento de texto en el índice especificado. |
| [get_Item](#get_Item-int-) | Obtiene el elemento de segmento de texto en el índice especificado. |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [iterator](#iterator--) | Devuelve un enumerador para toda la colección. |
| [remove](#remove-com.aspose.pdf.TextSegment-) | Elimina el elemento especificado de la colección. |
| [size](#size--) | Obtiene el número de elementos de objeto {@code TextSegment} realmente contenidos en la colección. |

### add {#add-com.aspose.pdf.TextSegment-}
Agrega el elemento de segmento de texto en el índice especificado.

### clear {#clear--}
```
public void clear()
```

Elimina todos los elementos de la colección.

### contains {#contains-com.aspose.pdf.TextSegment-}
Determina si la colección contiene un valor específico.

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina el elemento de segmento de texto en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

Obtiene el elemento de segmento de texto en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice dentro de la colección. |

**Returns:**
Objeto TextSegment.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a la colección.

**Returns:**
Elemento Object

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene un valor que indica si la colección es de solo lectura

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < TextSegment > iterator()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.TextSegment-}
Elimina el elemento especificado de la colección.

### size {#size--}
```
public int size()
```

Obtiene el número de elementos de objeto {@code TextSegment} realmente contenidos en la colección.

**Returns:**
valor int
