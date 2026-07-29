---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa BoundsCheckableList - envoltorio alrededor de System.Collections.Generic.List."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Representa BoundsCheckableList - envoltorio alrededor de System.Collections.Generic.List.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Inicializa una nueva instancia de la clase BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Inicializa una nueva instancia de la clase BoundsCheckableList. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addItem](#addItem-T-) | Agrega un objeto al final de System.Collections.Generic.List según el parámetro "boundsCheckMode". |
| [clear](#clear--) | Elimina todos los elementos de System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Determina si un elemento está en System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Copia todo System.Collections.Generic.List a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [get_Item](#get_Item-int-) | Obtiene o establece el párrafo desde o hacia la colección. |
| [indexOfItem](#indexOfItem-T-) | Busca el objeto especificado y devuelve el índice basado en cero de la primera aparición dentro de todo System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Inserta un elemento en System.Collections.Generic.List en el índice especificado. |
| [isReadOnly](#isReadOnly--) | Obtiene el valor que indica si la colección es de solo lectura. |
| [iterator](#iterator--) | Devuelve un enumerador que itera a través de System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Elimina el elemento en el índice especificado de la System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Elimina la primera aparición de un objeto específico de la System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Obtiene o establece el párrafo desde o hacia la colección. |
| [size](#size--) | Obtiene el número de elementos contenidos en la System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Actualiza el parámetro boundsCheckMode para la colección inicializada. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Actualiza el parámetro boundsCheckMode para la colección inicializada. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Inicializa una nueva instancia de la clase BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Inicializa una nueva instancia de la clase BoundsCheckableList.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| boundsCheckMode |  | El modo de verificación de límites. |
| containerWidth |  | El ancho del contenedor. |
| containerHeight |  | La altura del contenedor. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Agrega un objeto al final de System.Collections.Generic.List según el parámetro "boundsCheckMode".

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item |  | El objeto que se añadirá al final de la System.Collections.Generic.List. El valor puede ser "null" para tipos de referencia. |

### clear {#clear--}
```
public final void clear()
```

Elimina todos los elementos de System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Determina si un elemento está en System.Collections.Generic.List.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item |  | El objeto a localizar en la System.Collections.Generic.List. El valor puede ser null para tipos de referencia. |

**Returns:**
true si itemitem se encuentra en la System.Collections.Generic.List; de lo contrario, false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Copia todo System.Collections.Generic.List a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array |  | El System.Array unidimensional que es el destino de los elementos copiados de la System.Collections.Generic.List. El System.Array debe tener indexación basada en cero. |
| arrayIndex |  | El índice basado en cero en array donde comienza la copia. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Obtiene o establece el párrafo desde o hacia la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice del párrafo. |

**Returns:**
el elemento en el índice especificado.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Busca el objeto especificado y devuelve el índice basado en cero de la primera aparición dentro de todo System.Collections.Generic.List.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item |  | El objeto a localizar en la System.Collections.Generic.List. El valor puede ser null para tipos de referencia. |

**Returns:**
El índice basado en cero de la primera aparición de itemitem dentro de toda la System.Collections.Generic.List, si se encuentra; de lo contrario, –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Inserta un elemento en System.Collections.Generic.List en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice basado en cero en el que se debe insertar item. |
| item |  | El objeto a insertar. El valor puede ser nulo para tipos de referencia. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene el valor que indica si la colección es de solo lectura.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Devuelve un enumerador que itera a través de System.Collections.Generic.List.

**Returns:**
Un enumerador para el System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de la System.Collections.Generic.List.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice basado en cero del elemento a eliminar. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Elimina la primera aparición de un objeto específico de la System.Collections.Generic.List.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item |  | El objeto a eliminar del System.Collections.Generic.List. El valor puede ser nulo para tipos de referencia. |

**Returns:**
true si itemitem se elimina correctamente; de lo contrario, false. Este método también devuelve false si itemitem no se encontró en el System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Obtiene o establece el párrafo desde o hacia la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice del párrafo. |

### size {#size--}
```
public final int size()
```

Obtiene el número de elementos contenidos en la System.Collections.Generic.List.

**Returns:**
El número de elementos contenidos en el System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Actualiza el parámetro boundsCheckMode para la colección inicializada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| boundsCheckMode |  | El modo de verificación de límites. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Actualiza el parámetro boundsCheckMode para la colección inicializada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| boundsCheckMode |  | El modo de verificación de límites. |
| containerWidth |  | El ancho del contenedor. |
| containerHeight |  | La altura del contenedor. |
