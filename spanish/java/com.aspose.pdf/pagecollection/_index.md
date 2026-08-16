---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Colección de páginas de documentos PDF."
type: docs
weight: 3340
url: /es/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Colección de páginas de documentos PDF.

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta el objeto visitante {@code AnnotationSelector} que proporciona funcionalidad para trabajar con anotaciones. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Acepta el objeto visitante {@code ImagePlacementAbsorber} que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Acepta el objeto visitante {@code TextAbsorber} que proporciona funcionalidad para trabajar con objetos de texto. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Acepta el objeto visitante {@code TextFragmentAbsorber} que proporciona funcionalidad para trabajar con objetos de texto. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Agrega una página a la colección. |
| [add](#add--) | Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [add](#add-java.lang.Iterable-) | Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [add](#add-java.util.List-) | Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [add](#add-com.aspose.pdf.Page-) | Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [add](#add-com.aspose.pdf.Page:A-) | Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [beginUpdate](#beginUpdate--) | Actualiza cuando comienzan los cambios de grupo. |
| [clear](#clear--) | Limpia la colección de páginas. |
| [contains](#contains-com.aspose.pdf.Page-) | Determina si esta instancia contiene el objeto. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Copia páginas al documento. |
| [delete](#delete--) | Elimina todas las páginas de la colección. |
| [delete](#delete-int-) | Elimina la página especificada. |
| [delete](#delete-java.lang.Integer:A-) | Elimina todas las páginas de la colección. |
| [endUpdate](#endUpdate--) | Actualiza cuando se completan los cambios de grupo. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Elimina todos los campos ubicados en las páginas y coloca sus valores en su lugar. |
| [freeMemory](#freeMemory--) | Borra los datos en caché |
| [get_Item](#get_Item-int-) | Obtiene la página por índice. |
| [getSyncRoot](#getSyncRoot--) | Obtiene el objeto de sincronización de la colección. |
| [getUnrestricted](#getUnrestricted-int-) | Devuelve la página por su índice. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Devuelve el índice de la página especificada. </p> |
| [insert](#insert-int-) | Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [insert](#insert-int-java.lang.Iterable-) | Inserta páginas de la colección en el documento. |
| [insert](#insert-int-java.util.List-) | Inserta páginas de la colección en el documento. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Inserta una página en la colección de páginas en el lugar especificado. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Inserta páginas del arreglo en el documento. |
| [isEmpty](#isEmpty--) | Devuelve TRUE si la colección está vacía. |
| [isReadOnly](#isReadOnly--) | Obtiene el valor que indica si la colección es de solo lectura. Siempre devuelve false. |
| [isSynchronized](#isSynchronized--) | Devuelve true si el objeto está sincronizado. |
| [iterator](#iterator--) | Devuelve el enumerador de páginas. |
| [remove](#remove-com.aspose.pdf.Page-) | Elimina el elemento especificado, lanza una excepción. |
| [size](#size--) | Obtiene el recuento de páginas en el documento. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta el objeto visitante {@code AnnotationSelector} que proporciona funcionalidad para trabajar con anotaciones.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Acepta el objeto visitante {@code ImagePlacementAbsorber} que proporciona funcionalidad para trabajar con objetos de colocación de imágenes.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Acepta el objeto visitante {@code TextAbsorber} que proporciona funcionalidad para trabajar con objetos de texto.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Acepta el objeto visitante {@code TextFragmentAbsorber} que proporciona funcionalidad para trabajar con objetos de texto.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Agrega una página a la colección.

### add {#add--}
```
public Page add()
```

Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

**Returns:**
Página añadida.

### add {#add-java.lang.Iterable-}
Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

**Returns:**
Página añadida.

### add {#add-java.util.List-}
Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

**Returns:**
Página añadida.

### add {#add-com.aspose.pdf.Page-}
Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

**Returns:**
Página añadida.

### add {#add-com.aspose.pdf.Page:A-}
Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

**Returns:**
Página añadida.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Actualiza cuando comienzan los cambios de grupo.

### clear {#clear--}
```
public void clear()
```

Limpia la colección de páginas.

### contains {#contains-com.aspose.pdf.Page-}
Determina si esta instancia contiene el objeto.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Copia páginas al documento.

### delete {#delete--}
```
public void delete()
```

Elimina todas las páginas de la colección.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina la página especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Número de página que será eliminada. Los números de página comienzan en 1. |

### delete {#delete-java.lang.Integer:A-}
Elimina todas las páginas de la colección.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Actualiza cuando se completan los cambios de grupo.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Elimina todos los campos ubicados en las páginas y coloca sus valores en su lugar.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Borra los datos en caché

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Obtiene la página por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice de la página. |

**Returns:**
Página recuperada.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene el objeto de sincronización de la colección.

**Returns:**
Objeto para sincronización

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Devuelve la página por su índice. {@code Page}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice de la página solicitada. Las páginas están numeradas a partir de 1. |

**Returns:**
Página solicitada

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Devuelve el índice de la página especificada. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Posición de la nueva página. |

**Returns:**
Página insertada.

### insert {#insert-int-java.lang.Iterable-}
Inserta páginas de la colección en el documento.

### insert {#insert-int-java.util.List-}
Inserta páginas de la colección en el documento.

### insert {#insert-int-com.aspose.pdf.Page-}
Inserta una página en la colección de páginas en el lugar especificado.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Inserta páginas del arreglo en el documento.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Devuelve TRUE si la colección está vacía.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene el valor que indica si la colección es de solo lectura. Siempre devuelve false.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Devuelve true si el objeto está sincronizado.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Devuelve el enumerador de páginas.

**Returns:**
Enumerador de páginas

### remove {#remove-com.aspose.pdf.Page-}
Elimina el elemento especificado, lanza una excepción.

### size {#size--}
```
public int size()
```

Obtiene el recuento de páginas en el documento.

**Returns:**
valor int
