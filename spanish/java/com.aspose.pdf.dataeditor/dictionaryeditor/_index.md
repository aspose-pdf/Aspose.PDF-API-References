---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase para acceder al diccionario de árbol de un documento (diccionario del documento, diccionario de página, diccionario de recursos)."
type: docs
weight: 70
url: /es/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Una clase para acceder al diccionario de árbol de un documento (diccionario del documento, diccionario de página, diccionario de recursos).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Los recursos son nulos. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Establecer ICosPdfPrimitive al diccionario. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Establecer {@link ICosPdfPrimitive} al diccionario. |
| [clear](#clear--) | Elimina todos los elementos del {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina si el DictionaryEditor contiene un valor específico. |
| [containsKey](#containsKey-java.lang.String-) | Determina si el {@link DictionaryEditor} contiene un elemento con la clave especificada. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia los elementos del DictionaryEditor a un Array , comenzando en un índice de Array particular. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene o establece el elemento con la clave especificada. |
| [getAllKeys](#getAllKeys--) | Colección completa de claves. Contiene claves editables y no editables. |
| [getKeys](#getKeys--) | Colección de claves editables. |
| [getValues](#getValues--) | Obtiene un {@link ICollection} que contiene los valores en el {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si el {@link DictionaryEditor} es de solo lectura. |
| [iterator](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Elimina la primera aparición de un objeto específico del DictionaryEditor . |
| [remove](#remove-java.lang.String-) | Elimina el elemento con la clave especificada del {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Obtiene o establece el elemento con la clave especificada. |
| [size](#size--) | Obtiene el número de elementos contenidos en el {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Los recursos son nulos.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Establecer ICosPdfPrimitive al diccionario.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Establecer {@link ICosPdfPrimitive} al diccionario.

### clear {#clear--}
```
public final void clear()
```

Elimina todos los elementos del {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina si el DictionaryEditor contiene un valor específico.

### containsKey {#containsKey-java.lang.String-}
Determina si el {@link DictionaryEditor} contiene un elemento con la clave especificada.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia los elementos del DictionaryEditor a un Array , comenzando en un índice de Array particular.

### get_Item {#get_Item-java.lang.String-}
Obtiene o establece el elemento con la clave especificada.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Colección completa de claves. Contiene claves editables y no editables.

**Returns:**
Iterable de instancia String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Colección de claves editables.

**Returns:**
Iterable de instancia String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Obtiene un {@link ICollection} que contiene los valores en el {@link DictionaryEditor}.

**Returns:**
Iterable de instancia ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene un valor que indica si el {@link DictionaryEditor} es de solo lectura.

**Returns:**
true si el {@link DictionaryEditor} es de solo lectura; de lo contrario, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Devuelve un enumerador que recorre la colección.

**Returns:**
Un enumerador que puede usarse para iterar a través de la colección.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Elimina la primera aparición de un objeto específico del DictionaryEditor .

### remove {#remove-java.lang.String-}
Elimina el elemento con la clave especificada del {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Obtiene o establece el elemento con la clave especificada.

### size {#size--}
```
public final int size()
```

Obtiene el número de elementos contenidos en el {@link DictionaryEditor}.

**Returns:**
valor int

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos.
