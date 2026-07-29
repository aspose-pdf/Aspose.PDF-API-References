---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa la colección de XFormCollection."
type: docs
weight: 5600
url: /es/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Clase que representa la colección de XFormCollection.

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Agrega un nuevo XForm a la colección. |
| [clear](#clear--) | Elimina todos los elementos de la colección. |
| [contains](#contains-com.aspose.pdf.XForm-) | Determina si la colección contiene un valor específico. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Copia XFormCollection a la colección. |
| [delete](#delete--) | Elimina todos los XForms de la colección. |
| [delete](#delete-int-) | Eliminar XForm de la colección |
| [delete](#delete-java.lang.String-) | Elimina todos los XForms de la colección. |
| [freeMemory](#freeMemory--) | Limpia los datos en caché, libera memoria, etc. |
| [get_Item](#get_Item-int-) | Devuelve XForm por índice. |
| [get_Item](#get_Item-java.lang.String-) | Devuelve XForm por su nombre. Se lanza una excepción si no se encuentra un XForm con el nombre especificado. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Devuelve el nombre del formulario en esta colección de formularios |
| [getSyncRoot](#getSyncRoot--) | Objeto de sincronización. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
| [isSynchronized](#isSynchronized--) | Devuelve true si el objeto está sincronizado. |
| [iterator](#iterator--) | Devuelve el enumerador de la colección. |
| [remove](#remove-com.aspose.pdf.XForm-) | Elimina el elemento especificado de la colección. |
| [size](#size--) | Obtiene la cantidad de XForms en la colección. |

### add {#add-com.aspose.pdf.XForm-}
Agrega un nuevo XForm a la colección.

### clear {#clear--}
```
public void clear()
```

Elimina todos los elementos de la colección.

### contains {#contains-com.aspose.pdf.XForm-}
Determina si la colección contiene un valor específico.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Copia XFormCollection a la colección.

### delete {#delete--}
```
public void delete()
```

Elimina todos los XForms de la colección.

### delete {#delete-int-}
```
public void delete(int index)
```

Eliminar XForm de la colección

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del XForm que debe eliminarse |

### delete {#delete-java.lang.String-}
Elimina todos los XForms de la colección.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Limpia los datos en caché, libera memoria, etc.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Devuelve XForm por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice de XFormCollection. La numeración de XForms comienza en 1 |

**Returns:**
XForm recuperado

### get_Item {#get_Item-java.lang.String-}
Devuelve XForm por su nombre. Se lanza una excepción si no se encuentra un XForm con el nombre especificado.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Devuelve el nombre del formulario en esta colección de formularios

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objeto de sincronización.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


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

Devuelve true si el objeto está sincronizado.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Devuelve el enumerador de la colección.

**Returns:**
Enumerador de la colección

### remove {#remove-com.aspose.pdf.XForm-}
Elimina el elemento especificado de la colección.

### size {#size--}
```
public int size()
```

Obtiene la cantidad de XForms en la colección.

**Returns:**
valor int
