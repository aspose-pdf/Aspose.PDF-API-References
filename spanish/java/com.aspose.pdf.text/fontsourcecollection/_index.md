---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una colección de fuentes."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
Iterable < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

Representa una colección de fuentes.

## Campos

| Campo | Descripción |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | Evento CollectionChanged |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | Inicializa el objeto de colección |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | Agrega un nuevo objeto de origen de fuente a la colección. |
| [clear](#clear--) | Limpia la colección de origen de fuentes. |
| [contains](#contains-com.aspose.pdf.FontSource-) | Determina si un elemento está en la colección. |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [delete](#delete-com.aspose.pdf.FontSource-) | Elimina el elemento de origen de fuente. |
| [getItem](#getItem-int-) | Obtiene el elemento de fuente en el índice especificado. |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [iterator](#iterator--) | Devuelve un enumerador para toda la colección. |
| [remove](#remove-com.aspose.pdf.FontSource-) | Elimina el elemento de origen de fuente. |
| [size](#size--) | Obtiene el número de elementos de objeto Font realmente contenidos en la colección. |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

Evento CollectionChanged

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

Inicializa el objeto de colección

### add {#add-com.aspose.pdf.FontSource-}
Agrega un nuevo objeto de origen de fuente a la colección.

### clear {#clear--}
```
public void clear()
```

Limpia la colección de origen de fuentes.

### contains {#contains-com.aspose.pdf.FontSource-}
Determina si un elemento está en la colección.

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino.

### delete {#delete-com.aspose.pdf.FontSource-}
Elimina el elemento de origen de fuente.

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

Obtiene el elemento de fuente en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice dentro de la colección. |

**Returns:**
Objeto de origen de fuente.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a la colección.

**Returns:**
Elemento Object

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.FontSource-}
Elimina el elemento de origen de fuente.

### size {#size--}
```
public int size()
```

Obtiene el número de elementos de objeto Font realmente contenidos en la colección.

**Returns:**
valor int
