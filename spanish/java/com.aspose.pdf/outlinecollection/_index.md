---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la jerarquía del esquema del documento."
type: docs
weight: 3260
url: /es/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Representa la jerarquía del esquema del documento.

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Agrega un elemento de esquema a la colección. |
| [clear](#clear--) | Elimina todos los elementos de la colección. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Aún no soportado. Verifica si la colección contiene el elemento dado. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copia los elementos de esquema a un System.Array, comenzando en un índice específico de System.Array. |
| [delete](#delete--) | Elimina todos los elementos de esquema del esquema del documento. |
| [delete](#delete-java.lang.String-) | Elimina todos los elementos de esquema del esquema del documento. |
| [get_Item](#get_Item-int-) | Obtiene el elemento de esquema de la colección por índice. |
| [getFirst](#getFirst--) | Obtiene un elemento de esquema que representa el primer elemento de nivel superior en el esquema. |
| [getLast](#getLast--) | Obtiene un elemento de esquema que representa el último elemento de nivel superior en el esquema. |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a esta colección. |
| [getVisibleCount](#getVisibleCount--) | Count es la suma del número de elementos de esquema descendientes visibles en todos los niveles. Nota: por favor no confunda con Count que es el número de elementos en la colección. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos). |
| [iterator](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [next](#next--) |  |
| [remove](#remove-int-) | Elimina el elemento por índice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Aún no soportado. Siempre lanza una excepción. |
| [size](#size--) | Obtiene el número total de elementos de esquema (marcadores) en todos los niveles del esquema del documento. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Agrega un elemento de esquema a la colección.

### clear {#clear--}
```
public void clear()
```

Elimina todos los elementos de la colección.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Aún no soportado. Verifica si la colección contiene el elemento dado.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copia los elementos de esquema a un System.Array, comenzando en un índice específico de System.Array.

### delete {#delete--}
```
public void delete()
```

Elimina todos los elementos de esquema del esquema del documento.

### delete {#delete-java.lang.String-}
Elimina todos los elementos de esquema del esquema del documento.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Obtiene el elemento de esquema de la colección por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del elemento solicitado. |

**Returns:**
Objeto OutlineItemCollection

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Obtiene un elemento de esquema que representa el primer elemento de nivel superior en el esquema.

**Returns:**
Objeto OutlineItemCollection

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Obtiene un elemento de esquema que representa el último elemento de nivel superior en el esquema.

**Returns:**
Objeto OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a esta colección.

**Returns:**
Objeto para sincronización

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count es la suma del número de elementos de esquema descendientes visibles en todos los niveles. Nota: por favor no confunda con Count que es el número de elementos en la colección.

**Returns:**
valor int

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene un valor que indica si la colección es de solo lectura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Devuelve un enumerador que recorre la colección.

**Returns:**
Un objeto System.Collections.IEnumerator que puede usarse para iterar a través de la colección.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Elimina el elemento por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del elemento a eliminar. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Aún no soportado. Siempre lanza una excepción.

### size {#size--}
```
public int size()
```

Obtiene el número total de elementos de esquema (marcadores) en todos los niveles del esquema del documento.

**Returns:**
valor int
