---
title: "ElementList"
linktitle: "ElementList"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una colección ordenada de elementos."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Representa una colección ordenada de elementos.

## Métodos

| Método | Descripción |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Agregar elemento a la lista. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Obtiene el número de elementos en el ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insertar elemento en la lista. |
| [item](#item-int-) | Recupera un elemento en el índice dado. |
| [iterator](#iterator--) | Obtiene un enumerador que recorre la colección de elementos. |
| [removeAt](#removeAt-int-) | Eliminar elemento de la lista. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Eliminar elemento de la lista. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Agregar elemento a la lista.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Obtiene el número de elementos en el ElementList.

**Returns:**
valor int

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insertar elemento en la lista.

### item {#item-int-}
```
public abstract Element item(int index)
```

Recupera un elemento en el índice dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice en la lista de elementos. |

**Returns:**
El {@code /Aspose.Pdf.LogicalStructure.Element} con el índice especificado en la colección. Si {@code index} es mayor o igual que el número de elementos en la lista, esto devuelve null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Obtiene un enumerador que recorre la colección de elementos.

**Returns:**
Un enumerador usado para iterar a través de la colección de elementos.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Eliminar elemento de la lista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice a eliminar. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Eliminar elemento de la lista.
