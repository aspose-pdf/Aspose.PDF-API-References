---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una colección de operadores"
type: docs
weight: 3190
url: /es/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Clase que representa una colección de operadores

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | ¡Solo para uso interno! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | ¡Solo para uso interno! |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante IOperatorSelector para procesar operadores. |
| [add](#add-java.lang.Iterable-) | Agrega a la colección todos los operadores de otra colección. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Agrega un nuevo operador a la colección. </p> <hr> <p> El ejemplo muestra cómo agregar operadores al final de page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Agrega operadores al final de los operadores de contenido. </p> <hr> <p> El ejemplo muestra cómo agregar un operador al final del contenido de la página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización del contenido. |
| [clear](#clear--) | <p> Elimina todos los operadores de la lista. </p> <hr> <p> El ejemplo muestra cómo limpiar el contenido de la página. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Ejecuta tareas definidas por la aplicación asociadas con la liberación, el desalojo o el reinicio de recursos no administrados. |
| [contains](#contains-com.aspose.pdf.Operator-) | Devuelve true si la colección contiene el operador especificado. |
| [delete](#delete-int-) | <p> Elimina un operador de la colección. </p> <hr> <p> El ejemplo muestra cómo eliminar un operador por su índice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Elimina operadores de la colección. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Elimina operadores de la colección. </p> <hr> <p> El ejemplo muestra cómo eliminar un operador del contenido de la página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | versión interna sin restricciones de Delete(index) |
| [dispose](#dispose--) | Ejecuta tareas definidas por la aplicación asociadas con la liberación, el desalojo o el reinicio de recursos no administrados. |
| [get_Item](#get_Item-int-) | <p> Obtiene el operador por su índice. </p> <hr> El ejemplo muestra cómo obtener el operador del contenido de la página por índice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Versión interna sin restricciones del indexador |
| [insert](#insert-int-java.lang.Iterable-) | Inserta operadores en la posición dada. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Inserta un operador en la colección. </p> <hr> <p> El ejemplo muestra cómo insertar un operador en el contenido de la página. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Inserta operadores en la posición dada. </p> <hr> <p> El ejemplo muestra cómo insertar un operador en el contenido de la página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Obtiene el estado entre corchetes de la secuencia de operadores, es decir, si estos operadores están dentro de bloques q - Q |
| [isCommandsParsed](#isCommandsParsed--) | Obtiene los comandos analizados |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica si la colección está limitada a la extracción rápida de texto |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura. |
| [iterator](#iterator--) | Devuelve un enumerador para la colección |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Obtiene la cantidad de operadores que describen el contenido de la página sin inicializarlos. |
| [remove](#remove-com.aspose.pdf.Operator-) | Elimina un operador de la colección. |
| [replace](#replace-java.lang.Iterable-) | Reemplaza operadores en la colección con otros operadores. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Reemplaza operadores en la colección con otros operadores. |
| [resumeUpdate](#resumeUpdate--) | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| [resumeUpdate](#resumeUpdate-boolean-) | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. Marca todos los operadores como "changed" si el parámetro invalidate es verdadero. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Establece el operador por su índice. |
| [size](#size--) | Obtiene el recuento de operadores en la colección. |
| [suppressUpdate](#suppressUpdate--) | Suprime la actualización de datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate. |
| [toList](#toList--) | Devuelve la lista de operadores. |
| [toString](#toString--) | Devuelve la representación textual del operador. |
| [updateData](#updateData--) | Actualiza el flujo de objetos. |
| [updateNormalizedData](#updateNormalizedData--) | Actualiza el flujo de objetos corrigiendo la ausencia de operadores GSave/GRestore. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
¡Solo para uso interno!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
¡Solo para uso interno!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante IOperatorSelector para procesar operadores.

### add {#add-java.lang.Iterable-}
Agrega a la colección todos los operadores de otra colección.

### add {#add-com.aspose.pdf.Operator-}
<p> Agrega un nuevo operador a la colección. </p> <hr> <p> El ejemplo muestra cómo agregar operadores al final de page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Agrega operadores al final de los operadores de contenido. </p> <hr> <p> El ejemplo muestra cómo agregar un operador al final del contenido de la página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización del contenido.

### clear {#clear--}
```
public void clear()
```

<p> Elimina todos los operadores de la lista. </p> <hr> <p> El ejemplo muestra cómo limpiar el contenido de la página. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Ejecuta tareas definidas por la aplicación asociadas con la liberación, el desalojo o el reinicio de recursos no administrados.

### contains {#contains-com.aspose.pdf.Operator-}
Devuelve true si la colección contiene el operador especificado.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Elimina un operador de la colección. </p> <hr> <p> El ejemplo muestra cómo eliminar un operador por su índice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del operador que debe eliminarse. La numeración de los operadores comienza en 1. |

### delete {#delete-java.lang.Iterable-}
Elimina operadores de la colección.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Elimina operadores de la colección. </p> <hr> <p> El ejemplo muestra cómo eliminar un operador del contenido de la página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

versión interna sin restricciones de Delete(index)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

### dispose {#dispose--}
```
public final void dispose()
```

Ejecuta tareas definidas por la aplicación asociadas con la liberación, el desalojo o el reinicio de recursos no administrados.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Obtiene el operador por su índice. </p> <hr> El ejemplo muestra cómo obtener el operador del contenido de la página por índice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Versión interna sin restricciones del indexador

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | valor int |

**Returns:**
Objeto del operador

### insert {#insert-int-java.lang.Iterable-}
Inserta operadores en la posición dada.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Inserta un operador en la colección. </p> <hr> <p> El ejemplo muestra cómo insertar un operador en el contenido de la página. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Inserta operadores en la posición dada. </p> <hr> <p> El ejemplo muestra cómo insertar un operador en el contenido de la página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Obtiene el estado entre corchetes de la secuencia de operadores, es decir, si estos operadores están dentro de bloques q - Q

**Returns:**
valor booleano

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Obtiene los comandos analizados

**Returns:**
valor booleano

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Devuelve un enumerador para la colección

**Returns:**
Enumerador de la colección

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Obtiene la cantidad de operadores que describen el contenido de la página sin inicializarlos.

**Returns:**
valor int

### remove {#remove-com.aspose.pdf.Operator-}
Elimina un operador de la colección.

### replace {#replace-java.lang.Iterable-}
Reemplaza operadores en la colección con otros operadores.

### replace {#replace-com.aspose.pdf.Operator:A-}
Reemplaza operadores en la colección con otros operadores.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. Marca todos los operadores como "changed" si el parámetro invalidate es verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updateAll |  | Si es verdadero, todos los operadores en la colección se marcan como actualizados. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Establece el operador por su índice.

### size {#size--}
```
public int size()
```

Obtiene el recuento de operadores en la colección.

**Returns:**
valor int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime la actualización de datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Devuelve la lista de operadores.

**Returns:**
lista de operadores.

### toString {#toString--}
```
public String toString()
```

Devuelve la representación textual del operador.

**Returns:**
Representación textual del operador.

### updateData {#updateData--}
```
public void updateData()
```

Actualiza el flujo de objetos.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Actualiza el flujo de objetos corrigiendo la ausencia de operadores GSave/GRestore.
