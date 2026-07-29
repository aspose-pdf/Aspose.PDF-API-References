---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase para acceder al diccionario de un objeto."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Una clase para acceder al diccionario de un objeto.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Crea un diccionario a partir de los recursos. @exception ArgumentNullException Los recursos son nulos. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Establecer ICosPdfPrimitive al diccionario. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Establece {@link ICosPdfPrimitive} en el diccionario. @exception ArgumentException Lanza una excepción si la clave/valor no pueden ser editados o eliminados. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Agregar par de elementos. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Agregar elemento. |
| [clear](#clear--) | Elimina todos los elementos del {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina si el CosPdfDictionary contiene un valor específico. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Devuelve true si contiene el elemento |
| [containsKey](#containsKey-java.lang.String-) | Determina si el {@link CosPdfDictionary} contiene un elemento con la clave especificada. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia los elementos del CosPdfDictionary a un Array, comenzando en un índice de Array particular. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copiar a Array |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Crea un diccionario vacío que se adjuntará al documento. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Crea un diccionario vacío que se adjuntará a la página. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene o establece el elemento con la clave especificada. |
| [getAllKeys](#getAllKeys--) | Colección completa de claves. Contiene claves editables y no editables. |
| [getKeys](#getKeys--) | Colección de claves editables. |
| [getValues](#getValues--) | Obtiene una {@link ICollection} que contiene los valores en el {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si el {@link CosPdfDictionary} es de solo lectura. |
| [iterator](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Elimina la primera aparición de un objeto específico del CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Elimina el elemento con la clave especificada del {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Eliminar elemento |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Eliminar elemento por clave. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Obtiene o establece el elemento con la clave especificada. @exception ArgumentNullException La clave es nula. @exception KeyNotFoundException La propiedad se recupera y la clave no se encuentra. @exception ArgumentException Lanza una excepción si la clave no puede ser editada/establecida. |
| [size](#size--) | Obtiene el número de elementos contenidos en el {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Intenta convertir esta instancia a {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Intentar obtener el valor |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Crea un diccionario a partir de los recursos. @exception ArgumentNullException Los recursos son nulos.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Establecer ICosPdfPrimitive al diccionario.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Establece {@link ICosPdfPrimitive} en el diccionario. @exception ArgumentException Lanza una excepción si la clave/valor no pueden ser editados o eliminados.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Agregar par de elementos.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Agregar elemento.

### clear {#clear--}
```
public final void clear()
```

Elimina todos los elementos del {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina si el CosPdfDictionary contiene un valor específico.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Devuelve true si contiene el elemento

### containsKey {#containsKey-java.lang.String-}
Determina si el {@link CosPdfDictionary} contiene un elemento con la clave especificada.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia los elementos del CosPdfDictionary a un Array, comenzando en un índice de Array particular.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copiar a Array

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Crea un diccionario vacío que se adjuntará al documento.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Crea un diccionario vacío que se adjuntará a la página.

### get_Item {#get_Item-java.lang.String-}
Obtiene o establece el elemento con la clave especificada.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Colección completa de claves. Contiene claves editables y no editables.

**Returns:**
Lista de valores String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Colección de claves editables.

**Returns:**
Lista de valores String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Obtiene una {@link ICollection} que contiene los valores en el {@link CosPdfDictionary}.

**Returns:**
Lista de instancias de ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene un valor que indica si el {@link CosPdfDictionary} es de solo lectura.

**Returns:**
true si el {@link CosPdfDictionary} es de solo lectura; de lo contrario, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Devuelve un enumerador que recorre la colección.

**Returns:**
Un enumerador que puede usarse para iterar a través de la colección.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Elimina la primera aparición de un objeto específico del CosPdfDictionary.

### remove {#remove-java.lang.String-}
Elimina el elemento con la clave especificada del {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Eliminar elemento

### removeItemByKey {#removeItemByKey-java.lang.String-}
Eliminar elemento por clave.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Obtiene o establece el elemento con la clave especificada. @exception ArgumentNullException La clave es nula. @exception KeyNotFoundException La propiedad se recupera y la clave no se encuentra. @exception ArgumentException Lanza una excepción si la clave no puede ser editada/establecida.

### size {#size--}
```
public final int size()
```

Obtiene el número de elementos contenidos en el {@link CosPdfDictionary}.

**Returns:**
valor int

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Intenta convertir esta instancia a {@link CosPdfDictionary}.

**Returns:**
null si la instancia no es {@link CosPdfDictionary}; de lo contrario {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Intentar obtener el valor
