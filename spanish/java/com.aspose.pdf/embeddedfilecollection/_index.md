---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa la colección de archivos incrustados."
type: docs
weight: 1200
url: /es/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Clase que representa la colección de archivos incrustados.

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Agrega la especificación de archivo incrustado a la colección. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Agrega el archivo a los archivos incrustados con la clave especificada. |
| [clear](#clear--) | Eliminar todos los archivos incrustados del documento. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Determina si la colección contiene la FileSpecification especificada. No compatible. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Copia la matriz de objetos FileSpecification en la colleciton. |
| [delete](#delete--) | Eliminar todos los archivos incrustados del documento. |
| [delete](#delete-java.lang.String-) | Eliminar todos los archivos incrustados del documento. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Elimina el archivo de la colección por su clave en la colección. |
| [findByName](#findByName-java.lang.String-) | Devuelve el archivo incrustado por su nombre. |
| [get_Item](#get_Item-int-) | Obtiene el archivo incrustado por su índice. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene el archivo incrustado por su nombre. |
| [getKeys](#getKeys--) | Devuelve la lista de claves de archivos adjuntos. |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a esta colección. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Comprueba si la estructura de Archivos incrustados existe. Devuelve TRUE si la estructura existe, y FALSE si no. Si el documento nunca ha contenido archivos incrustados, esta estructura no se creó y está ausente. |
| [isReadOnly](#isReadOnly--) | Determina si la colección es de solo lectura. Siempre devuelve false. |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Devuelve el enumerador de la colleciton. |
| [iterator](#iterator--) | Devuelve el enumerador de la colleciton. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Elimina la FileSpecification especificada de la colección. No compatible. |
| [size](#size--) | Obtiene el número de archivos incrustados en la colección. |

### add {#add-com.aspose.pdf.FileSpecification-}
Agrega la especificación de archivo incrustado a la colección.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Agrega el archivo a los archivos incrustados con la clave especificada.

### clear {#clear--}
```
public void clear()
```

Eliminar todos los archivos incrustados del documento.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Determina si la colección contiene la FileSpecification especificada. No compatible.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Copia la matriz de objetos FileSpecification en la colleciton.

### delete {#delete--}
```
public void delete()
```

Eliminar todos los archivos incrustados del documento.

### delete {#delete-java.lang.String-}
Eliminar todos los archivos incrustados del documento.

### deleteByKey {#deleteByKey-java.lang.String-}
Elimina el archivo de la colección por su clave en la colección.

### findByName {#findByName-java.lang.String-}
Devuelve el archivo incrustado por su nombre.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Obtiene el archivo incrustado por su índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del archivo incrustado. La numeración comienza en 1. |

**Returns:**
Especificación del archivo incrustado recuperado

### get_Item {#get_Item-java.lang.String-}
Obtiene el archivo incrustado por su nombre.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Devuelve la lista de claves de archivos adjuntos.

**Returns:**
Lista de valores String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a esta colección.

**Returns:**
Objeto para sincronización

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Comprueba si la estructura de Archivos incrustados existe. Devuelve TRUE si la estructura existe, y FALSE si no. Si el documento nunca ha contenido archivos incrustados, esta estructura no se creó y está ausente.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determina si la colección es de solo lectura. Siempre devuelve false.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Devuelve el enumerador de la colleciton.

**Returns:**
Enumerador de la colleciton.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Devuelve el enumerador de la colleciton.

**Returns:**
Enumerador de la colleciton.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Elimina la FileSpecification especificada de la colección. No compatible.

### size {#size--}
```
public int size()
```

Obtiene el número de archivos incrustados en la colección.

**Returns:**
valor int
