---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Diccionario de apariencia de anotación que especifica cómo debe presentarse visualmente la anotación en la página."
type: docs
weight: 150
url: /es/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Diccionario de apariencia de anotación que especifica cómo debe presentarse visualmente la anotación en la página.

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Agrega un elemento con la clave y el valor proporcionados. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Agrega un par con clave y valor al diccionario. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Agregar X form para la clave especificada. |
| [clear](#clear--) | Elimina todos los elementos del diccionario. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [containsKey](#containsKey-java.lang.String-) | Determina si este diccionario contiene la clave especificada. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Devuelve un objeto IDictionaryEnumerator para el diccionario. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia los elementos de la ICollection a un Array, comenzando en un índice de Array específico. |
| [get_Item](#get_Item-java.lang.String-) | Representa una forma conveniente para obtener flujos de apariencia. |
| [getDict](#getDict--) | Obtiene el diccionario pdf |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state valores, donde N - apariencia normal, R - apariencia rollover, D - apariencia presionada y state - el nombre del estado (p. ej., On, Off para casillas de verificación). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state valores, donde N - apariencia normal, R - apariencia rollover, D - apariencia presionada y state - el nombre del estado (p. ej., On, Off para casillas de verificación). |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al diccionario. |
| [getValues_](#getValues_--) | Obtiene la lista de los valores del diccionario. La colección resultante contiene la lista de objetos XForm. |
| [getValues](#getValues--) | Obtiene la lista de los valores del diccionario. La colección resultante contiene la lista de objetos XForm. |
| [isFixedSize](#isFixedSize--) | Obtiene un valor que indica si el diccionario tiene un tamaño fijo. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si el diccionario es de solo lectura. |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso al diccionario está sincronizado (seguro para subprocesos). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumerador para la colección. |
| [iterator](#iterator--) | Devuelve un objeto IDictionaryEnumerator para el diccionario. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Elimina el par clave/valor de la colección. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Elimina la clave del diccionario. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Obtiene el número de elementos contenidos en el diccionario. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### add {#add-java.lang.Object-java.lang.Object-}
Agrega un elemento con la clave y el valor proporcionados.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Agrega un par con clave y valor al diccionario.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Agregar X form para la clave especificada.

### clear {#clear--}
```
public void clear()
```

Elimina todos los elementos del diccionario.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Comprueba si el par clave-valor especificado está contenido en el diccionario.

### containsKey {#containsKey-java.lang.String-}
Determina si este diccionario contiene la clave especificada.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Devuelve un objeto IDictionaryEnumerator para el diccionario. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia los elementos de la ICollection a un Array, comenzando en un índice de Array específico.

### get_Item {#get_Item-java.lang.String-}
Representa una forma conveniente para obtener flujos de apariencia.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Obtiene el diccionario pdf

**Returns:**
Objeto IPdfDictionary

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Obtiene las claves del diccionario. Si el diccionario de apariencia tiene subdiccionarios, entonces {@code Keys} contiene valores (N|R|D).state, donde N - apariencia normal, R - apariencia rollover, D - apariencia presionada y state - el nombre del estado (p. ej., On, Off para casillas de verificación).

**Returns:**
Lista de valores String

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtiene las claves del diccionario. Si el diccionario de apariencia tiene subdiccionarios, entonces {@code Keys} contiene valores (N|R|D).state, donde N - apariencia normal, R - apariencia rollover, D - apariencia presionada y state - el nombre del estado (p. ej., On, Off para casillas de verificación).

**Returns:**
Lista de valores String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso al diccionario.

**Returns:**
Objeto para sincronización

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Obtiene la lista de los valores del diccionario. La colección resultante contiene la lista de objetos XForm.

**Returns:**
Lista de valores XForm

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Obtiene la lista de los valores del diccionario. La colección resultante contiene la lista de objetos XForm.

**Returns:**
Lista de valores XForm

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Obtiene un valor que indica si el diccionario tiene un tamaño fijo.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene un valor que indica si el diccionario es de solo lectura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtiene un valor que indica si el acceso al diccionario está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumerador para la colección.

**Returns:**
enumerador de los elementos de la colección.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Devuelve un objeto IDictionaryEnumerator para el diccionario.

**Returns:**
Enumerador del diccionario.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Elimina el par clave/valor de la colección.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Elimina la clave del diccionario.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Obtiene el número de elementos contenidos en el diccionario.

**Returns:**
valor int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra.
