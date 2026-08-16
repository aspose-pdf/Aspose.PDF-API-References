---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa una colección de fuentes. </p> <hr> <pre> El ejemplo muestra cómo hacer que todas las fuentes declaradas en la página estén incrustadas. // Abrir documento Document doc = new."
type: docs
weight: 1670
url: /es/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Representa una colección de fuentes. </p> <hr> <pre> El ejemplo muestra cómo hacer que todas las fuentes declaradas en la página estén incrustadas. // Abrir documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // asegurar que todas las fuentes declaradas en los recursos de la página estén incrustadas // notar que si las fuentes se declaran en los recursos del formulario no son accesibles desde los recursos de la página for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save(\"D:\\\\Tests\\\\input.pdf\"); </pre> <hr> <p> Las colecciones de fuentes representadas por la clase {@code FontCollection} se utilizan en varios escenarios. Por ejemplo, en recursos con la propiedad {@code Resources.Fonts}. </p>

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Agrega una fuente a la colección. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Agrega una nueva fuente a los recursos de fuentes y devuelve el nombre asignado automáticamente al recurso de fuente. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Agregar una nueva fuente a la colección de fuentes. |
| [add](#add-java.lang.String-java.lang.String-) | Agrega a los recursos de fuentes una nueva entrada de fuente con el nombre base de fuente especificado. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Agrega una fuente a la colección. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Determina si la colección contiene un valor específico. |
| [contains](#contains-java.lang.String-) | Comprueba si la fuente existe en la colección de fuentes. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [delete](#delete-java.lang.String-) | Elimina la fuente con el nombre de recurso especificado. |
| [get_Item](#get_Item-int-) | Obtiene el elemento de fuente en el índice especificado. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene la fuente de la colección por nombre de fuente. Se lanza una excepción si no se encuentra la fuente. |
| [getFontsDictionary](#getFontsDictionary--) | Obtener objeto IPdfDictionary |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Devuelve un enumerador para toda la colección. |
| [iterator](#iterator--) | Devuelve un enumerador para toda la colección. |
| [remove](#remove-com.aspose.pdf.Font-) | Elimina el elemento especificado de la colección. |
| [size](#size--) | Obtiene el número de elementos objeto {@code Font} realmente contenidos en la colección. |

### add {#add-com.aspose.pdf.Font-}
Agrega una fuente a la colección.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Agrega una nueva fuente a los recursos de fuentes y devuelve el nombre asignado automáticamente al recurso de fuente.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Agregar una nueva fuente a la colección de fuentes.

### add {#add-java.lang.String-java.lang.String-}
Agrega a los recursos de fuentes una nueva entrada de fuente con el nombre base de fuente especificado.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Agrega una fuente a la colección. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Determina si la colección contiene un valor específico.

### contains {#contains-java.lang.String-}
Comprueba si la fuente existe en la colección de fuentes.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino.

### delete {#delete-java.lang.String-}
Elimina la fuente con el nombre de recurso especificado.

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Obtiene el elemento de fuente en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice dentro de la colección. |

**Returns:**
Objeto de fuente.

### get_Item {#get_Item-java.lang.String-}
Obtiene la fuente de la colección por nombre de fuente. Se lanza una excepción si no se encuentra la fuente.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Obtener objeto IPdfDictionary

**Returns:**
Objeto IPdfDictionary

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a la colección.

**Returns:**
Objeto para sincronización

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

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.Font-}
Elimina el elemento especificado de la colección.

### size {#size--}
```
public int size()
```

Obtiene el número de elementos objeto {@code Font} realmente contenidos en la colección.

**Returns:**
valor int
