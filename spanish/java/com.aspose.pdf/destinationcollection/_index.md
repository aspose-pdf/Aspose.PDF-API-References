---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "La clase representa la colección de todos los destinos (un árbol de nombres que asigna cadenas de nombres a destinos (ver 12.3.2.3, \"Named Destinations\") y (ver 7.7.4, \"Name Dictionary\")) en."
type: docs
weight: 960
url: /es/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Clase que representa la colección de todos los destinos (un árbol de nombres que asigna cadenas de nombres a destinos (ver 12.3.2.3, \"Named Destinations\") y (ver 7.7.4, \"Name Dictionary\")) en el documento pdf.

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Agrega el elemento especificado. |
| [clear](#clear--) | La colección es de solo lectura. Siempre lanza una excepción NotSupportedException. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina si esta instancia contiene el objeto. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia los elementos de la colección a una matriz, comenzando en un índice de matriz específico. |
| [get_Item](#get_Item-int-) | Obtiene el objeto de destino por índice. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Devuelve el destino explícito por nombre. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Devuelve el número de página del destino por nombre. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Devuelve el índice del destino en la colección. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
| [iterator](#iterator--) | Devuelve el enumerador. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Elimina el elemento especificado. |
| [size](#size--) | Obtiene el número de elementos contenidos en la colección. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Agrega el elemento especificado.

### clear {#clear--}
```
public void clear()
```

La colección es de solo lectura. Siempre lanza una excepción NotSupportedException.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina si esta instancia contiene el objeto.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia los elementos de la colección a una matriz, comenzando en un índice de matriz específico.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Obtiene el objeto de destino por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice del destino a obtener. |

**Returns:**
Destino.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Devuelve el destino explícito por nombre.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Devuelve el número de página del destino por nombre.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Devuelve el índice del destino en la colección.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene un valor que indica si la colección es de solo lectura.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Devuelve el enumerador.

**Returns:**
El enumerador.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Elimina el elemento especificado.

### size {#size--}
```
public int size()
```

Obtiene el número de elementos contenidos en la colección.

**Returns:**
valor int
