---
title: "Metadatos"
linktitle: "Metadatos"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Proporciona acceso al flujo de metadatos XMP."
type: docs
weight: 3050
url: /es/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Proporciona acceso al flujo de metadatos XMP.

## Métodos

| Método | Descripción |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Agrega un par con clave y valor al diccionario. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Agrega un valor a los metadatos. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Agrega la extensión pdf a los metadatos. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Agrega un valor a los metadatos. |
| [clear](#clear--) | Borra los metadatos. |
| [contains](#contains-java.lang.String-) | Comprueba si la clave está contenida en los metadatos. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [containsKey](#containsKey-java.lang.String-) | Determina si este diccionario contiene la clave especificada. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Copia los elementos de la colección en una matriz. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia los elementos de la colección en una matriz. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene datos de los metadatos. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Solo para uso interno. Obtiene el diccionario de campos de extensión. |
| [getExtensionFields](#getExtensionFields--) | <p> Obtiene el diccionario de campos de extensión. </p> |
| [getItem](#getItem-java.lang.String-) | Obtiene datos de los metadatos. |
| [getKeys](#getKeys--) | Obtiene la colección de claves de metadatos. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Devuelve el URI del espacio de nombres por prefijo. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Devuelve el prefijo por el URI del espacio de nombres. |
| [getSyncRoot](#getSyncRoot--) | Obtiene el objeto de sincronización de la colección. |
| [getValues](#getValues--) | Obtiene los valores en los metadatos. |
| [isFixedSize](#isFixedSize--) | Comprueba si la colección tiene tamaño fijo. |
| [isReadOnly](#isReadOnly--) | Comprueba si la colección es de solo lectura. |
| [isSynchronized](#isSynchronized--) | Comprueba si la colección está sincronizada. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Devuelve el enumerador del diccionario. |
| [iteratorIE](#iteratorIE--) | Obtiene el enumerador de la colección. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registra el URI del espacio de nombres. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registra el URI del espacio de nombres. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Elimina el par clave/valor de la colección. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Elimina la entrada de los metadatos. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Establece los datos a partir de los metadatos. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Establece los datos a partir de los metadatos. |
| [size](#size--) | Obtiene el recuento de elementos en la colección. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Agrega un par con clave y valor al diccionario.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Agrega un valor a los metadatos.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Agrega la extensión pdf a los metadatos.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Agrega un valor a los metadatos.

### clear {#clear--}
```
public void clear()
```

Borra los metadatos.

### contains {#contains-java.lang.String-}
Comprueba si la clave está contenida en los metadatos.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Comprueba si el par clave-valor especificado está contenido en el diccionario.

### containsKey {#containsKey-java.lang.String-}
Determina si este diccionario contiene la clave especificada.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Copia los elementos de la colección en una matriz.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia los elementos de la colección en una matriz.

### get_Item {#get_Item-java.lang.String-}
Obtiene datos de los metadatos.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Solo para uso interno. Obtiene el diccionario de campos de extensión.

**Returns:**
objeto interno

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Obtiene el diccionario de campos de extensión. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objeto

### getItem {#getItem-java.lang.String-}
Obtiene datos de los metadatos.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtiene la colección de claves de metadatos.

**Returns:**
objeto ICollection

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Devuelve el URI del espacio de nombres por prefijo.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Devuelve el prefijo por el URI del espacio de nombres.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene el objeto de sincronización de la colección.

**Returns:**
Objeto para sincronización

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Obtiene los valores en los metadatos.

**Returns:**
objeto ICollection

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Comprueba si la colección tiene tamaño fijo.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Comprueba si la colección es de solo lectura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Comprueba si la colección está sincronizada.

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Devuelve el enumerador del diccionario.

**Returns:**
Enumerador.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Obtiene el enumerador de la colección.

**Returns:**
objeto IEnumerator @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Registra el URI del espacio de nombres.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Registra el URI del espacio de nombres.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Elimina el par clave/valor de la colección.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Elimina la entrada de los metadatos.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Establece los datos a partir de los metadatos.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Establece los datos a partir de los metadatos.

### size {#size--}
```
public int size()
```

Obtiene el recuento de elementos en la colección.

**Returns:**
valor int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra.
