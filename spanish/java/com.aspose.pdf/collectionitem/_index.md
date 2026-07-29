---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase de elemento de colección. El elemento de colección contiene los datos descritos por el esquema de la colección."
type: docs
weight: 640
url: /es/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Representa una clase de elemento de colección. El elemento de colección contiene los datos descritos por el esquema de la colección.

## Métodos

| Método | Descripción |
| --- | --- |
| [getAllNames](#getAllNames--) | Obtiene una colección de todos los nombres de los valores del collection item. |
| [hasName](#hasName-java.lang.String-) | Comprueba si el nombre dado existe en el collection item. |
| [isEmpty](#isEmpty--) | Obtiene un valor que indica si el collection item está vacío. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Intenta obtener el valor de tipo DateTime del collection item mediante el nombre especificado. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Intenta obtener el valor double para el nombre especificado del collection item. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Intenta obtener el valor entero para un nombre especificado del collection item. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Intenta obtener el valor de texto con el nombre especificado del collection item. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Obtiene una colección de todos los nombres de los valores del collection item.

**Returns:**
lista de String

### hasName {#hasName-java.lang.String-}
Comprueba si el nombre dado existe en el collection item.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Obtiene un valor que indica si el collection item está vacío.

**Returns:**
true si el collection item está vacío; de lo contrario, false. Esta propiedad devuelve true si el collection item no contiene ningún valor, incluidos valores de cadena, valores double, valores enteros y valores de fecha. Si alguno de estos tipos de valor está presente en el collection item, esta propiedad devuelve false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Intenta obtener el valor de tipo DateTime del collection item mediante el nombre especificado.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Intenta obtener el valor double para el nombre especificado del collection item.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Intenta obtener el valor entero para un nombre especificado del collection item.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Intenta obtener el valor de texto con el nombre especificado del collection item.
