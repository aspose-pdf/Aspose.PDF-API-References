---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Colección ligera de operadores. Destinada a usarse en escenarios donde el flujo de contenido subyacente no está adjunto, y solo se requiere la colección de operadores como resultado."
type: docs
weight: 2700
url: /es/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Colección ligera de operadores. Destinada a usarse en escenarios donde el flujo de contenido subyacente no está adjunto, y solo se requiere la colección de operadores como resultado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Inicializar objeto |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Inicializar objeto |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Inicializar objeto |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Agregar operador |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Agregar LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización del contenido. |
| [clear](#clear--) | Borra la colección. |
| [contains](#contains-com.aspose.pdf.Operator-) | Verifica si el elemento está en la colección. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | eliminar interno Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Obtiene el operador por su índice. </p> <hr> <pre> El ejemplo muestra cómo obtener el operador del contenido de la página por índice. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Para uso interno getUnrestricted operator |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Insertar operador |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica si la colección está limitada a la extracción rápida de texto |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
| [iterator](#iterator--) | Devolver iterador |
| [remove](#remove-com.aspose.pdf.Operator-) | Elimina el operador de la colección. |
| [resumeUpdate](#resumeUpdate--) | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Establece el operador por su índice. <hr> <pre> El ejemplo muestra cómo obtener el operador del contenido de la página por índice. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Cantidad de operadores |
| [suppressUpdate](#suppressUpdate--) | Suprime la actualización de los datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate. |
| [toList](#toList--) | Devuelve la lista de operadores. |
| [updateData](#updateData--) | interno |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Inicializar objeto

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Inicializar objeto

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Inicializar objeto

### add {#add-com.aspose.pdf.Operator-}
Agregar operador

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Agregar LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización del contenido.

### clear {#clear--}
```
public void clear()
```

Borra la colección.

### contains {#contains-com.aspose.pdf.Operator-}
Verifica si el elemento está en la colección.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

eliminar interno Unrestrictedelement

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Obtiene el operador por su índice. </p> <hr> <pre> El ejemplo muestra cómo obtener el operador del contenido de la página por índice. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del operador. La numeración comienza en 1. |

**Returns:**
Operador del índice solicitado

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Para uso interno getUnrestricted operator

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

**Returns:**
Objeto del operador

### insert {#insert-int-com.aspose.pdf.Operator-}
Insertar operador

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indica si la colección está limitada a la extracción rápida de texto

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene un valor que indica si la colección es de solo lectura.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Devolver iterador

**Returns:**
{@code IGenericEnumerator<Operator>} objeto

### remove {#remove-com.aspose.pdf.Operator-}
Elimina el operador de la colección.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Establece el operador por su índice. <hr> <pre> El ejemplo muestra cómo obtener el operador del contenido de la página por índice. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Cantidad de operadores

**Returns:**
valor int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime la actualización de los datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Devuelve la lista de operadores.

**Returns:**
lista de operadores.

### updateData {#updateData--}
```
public void updateData()
```

interno
