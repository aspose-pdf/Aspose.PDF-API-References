---
title: "ElementList"
linktitle: "ElementList"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma coleção ordenada de elementos."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Representa uma coleção ordenada de elementos.

## Métodos

| Método | Descrição |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Adicionar elemento à lista. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Obtém o número de elementos na ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insira o elemento na lista. |
| [item](#item-int-) | Recupera um elemento no índice fornecido. |
| [iterator](#iterator--) | Obtém um enumerador que itera pela coleção de elementos. |
| [removeAt](#removeAt-int-) | Remova o elemento da lista. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Remova o elemento da lista. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Adicionar elemento à lista.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Obtém o número de elementos na ElementList.

**Returns:**
valor int

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insira o elemento na lista.

### item {#item-int-}
```
public abstract Element item(int index)
```

Recupera um elemento no índice fornecido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice na lista de elementos. |

**Returns:**
O {@code /Aspose.Pdf.LogicalStructure.Element} com o índice especificado na coleção. Se {@code index} for maior ou igual ao número de elementos na lista, isso retorna null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Obtém um enumerador que itera pela coleção de elementos.

**Returns:**
Um enumerador usado para iterar pela coleção de elementos.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Remova o elemento da lista.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice a remover. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Remova o elemento da lista.
