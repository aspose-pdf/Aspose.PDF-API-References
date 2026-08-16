---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description:
type: docs
weight: 50
url: /es/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Constructores

| Constructor | Descripción |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Agregar elemento a la lista. |
| [getCount](#getCount--) | Obtiene el número de elementos en el ElementList. |
| [item](#item-int-) | Recupera un elemento en el índice dado. |
| [iterator](#iterator--) | Obtiene un enumerador que recorre la colección de elementos. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Agregar elemento a la lista.

### getCount {#getCount--}
```
public int getCount()
```

Obtiene el número de elementos en el ElementList.

**Returns:**
valor int

### item {#item-int-}
```
public Element item(int index)
```

Recupera un elemento en el índice dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  |  |

**Returns:**
El /Aspose.Pdf.LogicalStructure.Element con el índice especificado en la colección. Si el índice es mayor o igual que el número de elementos en la lista, esto devuelve null.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Obtiene un enumerador que recorre la colección de elementos.

**Returns:**
Un enumerador usado para iterar a través de la colección de elementos.
