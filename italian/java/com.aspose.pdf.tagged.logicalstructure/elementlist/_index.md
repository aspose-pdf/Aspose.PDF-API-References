---
title: "ElementList"
linktitle: "ElementList"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una collezione ordinata di elementi."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Rappresenta una collezione ordinata di elementi.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Aggiungi elemento alla lista. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Ottiene il numero di elementi in ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Inserisci l'elemento nella lista. |
| [item](#item-int-) | Recupera un elemento all'indice specificato. |
| [iterator](#iterator--) | Ottiene un enumeratore che itera attraverso la collezione di elementi. |
| [removeAt](#removeAt-int-) | Rimuovi l'elemento dalla lista. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Rimuovi l'elemento dalla lista. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Aggiungi elemento alla lista.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Ottiene il numero di elementi in ElementList.

**Returns:**
valore int

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Inserisci l'elemento nella lista.

### item {#item-int-}
```
public abstract Element item(int index)
```

Recupera un elemento all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice nella lista degli elementi. |

**Returns:**
Il {@code /Aspose.Pdf.LogicalStructure.Element} con l'indice specificato nella collezione. Se {@code index} è maggiore o uguale al numero di elementi nella lista, questo restituisce null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Ottiene un enumeratore che itera attraverso la collezione di elementi.

**Returns:**
Un enumeratore usato per iterare attraverso la collezione di elementi.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Rimuovi l'elemento dalla lista.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice da rimuovere. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Rimuovi l'elemento dalla lista.
