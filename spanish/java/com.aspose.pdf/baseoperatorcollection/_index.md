---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase base para la colección de operadores."
type: docs
weight: 270
url: /es/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Representa la clase base para la colección de operadores.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Agrega un nuevo operador a la colección. |
| [cancelUpdate](#cancelUpdate--) | Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización del contenido. |
| [clear](#clear--) | Borra la colección. |
| [contains](#contains-com.aspose.pdf.Operator-) | Verifica si el elemento está en la colección. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | interno |
| [get_Item](#get_Item-int-) | Obtiene el operador por su índice. |
| [getUnrestricted](#getUnrestricted-int-) | Solo para uso interno |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Inserta el operador en la colección. |
| [isEmpty](#isEmpty--) | Devuelve TRUE si la colección está vacía. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica si la colección está limitada a la extracción rápida de texto |
| [isReadOnly](#isReadOnly--) | Devuelve true si la colección es de solo lectura. |
| [iterator](#iterator--) | Devuelve un enumerador para la colección |
| [remove](#remove-com.aspose.pdf.Operator-) | Elimina el operador de la colección. |
| [resumeUpdate](#resumeUpdate--) | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Establece el operador por su índice. |
| [size](#size--) | Obtiene el recuento de operadores en la colección. |
| [suppressUpdate](#suppressUpdate--) | Suprime la actualización de los datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate. |
| [toList](#toList--) | Devuelve la lista de opetator. |
| [updateData](#updateData--) | interno |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Agrega un nuevo operador a la colección.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización del contenido.

### clear {#clear--}
```
public abstract void clear()
```

Borra la colección.

### contains {#contains-com.aspose.pdf.Operator-}
Verifica si el elemento está en la colección.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

interno

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Obtiene el operador por su índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del operador. La numeración comienza en 1. |

**Returns:**
Operador del índice solicitado

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Solo para uso interno

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

**Returns:**
Objeto del operador

### insert {#insert-int-com.aspose.pdf.Operator-}
Inserta el operador en la colección.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Devuelve TRUE si la colección está vacía.

**Returns:**
valor booleano

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Indica si la colección está limitada a la extracción rápida de texto

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Devuelve true si la colección es de solo lectura.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Devuelve un enumerador para la colección

**Returns:**
Enumerador de la colección

### remove {#remove-com.aspose.pdf.Operator-}
Elimina el operador de la colección.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Establece el operador por su índice.

### size {#size--}
```
public abstract int size()
```

Obtiene el recuento de operadores en la colección.

**Returns:**
valor entero

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Suprime la actualización de los datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Devuelve la lista de opetator.

**Returns:**
lista de opetator.

### updateData {#updateData--}
```
public abstract void updateData()
```

interno
