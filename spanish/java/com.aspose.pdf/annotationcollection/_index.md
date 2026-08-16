---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una colección de anotaciones."
type: docs
weight: 80
url: /es/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Clase que representa una colección de anotaciones.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Constructor de AnnotationCollection. Crea una colección de anotaciones para las anotaciones en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un visitante para procesar la anotación. |
| [add](#add-com.aspose.pdf.Annotation-) | Añade la anotación a la colección. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Añade la anotación a la colección. Si la página está rotada, el rectángulo de la anotación se recalculará en consecuencia. |
| [clear](#clear--) | Elimina todas las anotaciones de la colección. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Comprueba si la anotación especificada pertenece a la colección. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Copia la matriz de anotaciones en la colección. |
| [delete](#delete--) | Elimina todas las anotaciones de la colección. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Elimina todas las anotaciones de la colección. |
| [delete](#delete-int-) | Elimina la anotación de la colección por índice. |
| [findByName](#findByName-java.lang.String-) | Devuelve la anotación por su nombre. |
| [get_Item](#get_Item-int-) | El índice del elemento a obtener. |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a com.aspose.pdf.AnnotationCollection está sincronizado (seguro para subprocesos). |
| [iterator](#iterator--) | Devuelve el enumerador de la colección. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Elimina la anotación especificada de la colección. |
| [size](#size--) | Obtiene el recuento de anotaciones en la colección. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Constructor de AnnotationCollection. Crea una colección de anotaciones para las anotaciones en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un visitante para procesar la anotación.

### add {#add-com.aspose.pdf.Annotation-}
Añade la anotación a la colección.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Añade la anotación a la colección. Si la página está rotada, el rectángulo de la anotación se recalculará en consecuencia.

### clear {#clear--}
```
public void clear()
```

Elimina todas las anotaciones de la colección.

### contains {#contains-com.aspose.pdf.Annotation-}
Comprueba si la anotación especificada pertenece a la colección.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Copia la matriz de anotaciones en la colección.

### delete {#delete--}
```
public void delete()
```

Elimina todas las anotaciones de la colección.

### delete {#delete-com.aspose.pdf.Annotation-}
Elimina todas las anotaciones de la colección.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina la anotación de la colección por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice de la anotación que se eliminará. |

### findByName {#findByName-java.lang.String-}
Devuelve la anotación por su nombre.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

El índice del elemento a obtener.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El valor del índice comienza en uno. |

**Returns:**
Objeto de anotación

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a com.aspose.pdf.AnnotationCollection.

**Returns:**
Objeto para sincronización

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

Obtiene un valor que indica si el acceso a com.aspose.pdf.AnnotationCollection está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Devuelve el enumerador de la colección.

**Returns:**
Objeto enumerador

### remove {#remove-com.aspose.pdf.Annotation-}
Elimina la anotación especificada de la colección.

### size {#size--}
```
public int size()
```

Obtiene el recuento de anotaciones en la colección.

**Returns:**
valor int
