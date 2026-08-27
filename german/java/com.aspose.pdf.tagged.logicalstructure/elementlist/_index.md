---
title: "ElementList"
linktitle: "ElementList"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine geordnete Sammlung von Elementen dar."
type: docs
weight: 40
url: /de/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Stellt eine geordnete Sammlung von Elementen dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Element zur Liste hinzufügen. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Gibt die Anzahl der Elemente in der ElementList zurück. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Element in die Liste einfügen. |
| [item](#item-int-) | Ruft ein Element am angegebenen Index ab. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung von Elementen durchläuft. |
| [removeAt](#removeAt-int-) | Element aus der Liste entfernen. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Element aus der Liste entfernen. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Element zur Liste hinzufügen.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Gibt die Anzahl der Elemente in der ElementList zurück.

**Returns:**
int-Wert

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Element in die Liste einfügen.

### item {#item-int-}
```
public abstract Element item(int index)
```

Ruft ein Element am angegebenen Index ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der Index in die Liste der Elemente. |

**Returns:**
Das {@code /Aspose.Pdf.LogicalStructure.Element} mit dem angegebenen Index in der Sammlung. Wenn {@code index} größer oder gleich der Anzahl der Elemente in der Liste ist, gibt dies null zurück.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Gibt einen Enumerator zurück, der die Sammlung von Elementen durchläuft.

**Returns:**
Ein Enumerator, der verwendet wird, um die Sammlung von Elementen zu durchlaufen.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Element aus der Liste entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Zu entfernender Index. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Element aus der Liste entfernen.
