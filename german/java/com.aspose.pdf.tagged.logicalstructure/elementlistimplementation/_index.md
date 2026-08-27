---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Aspose.PDF für Java API-Referenz"
description:
type: docs
weight: 50
url: /de/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Element zur Liste hinzufügen. |
| [getCount](#getCount--) | Gibt die Anzahl der Elemente in der ElementList zurück. |
| [item](#item-int-) | Ruft ein Element am angegebenen Index ab. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung von Elementen durchläuft. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Element zur Liste hinzufügen.

### getCount {#getCount--}
```
public int getCount()
```

Gibt die Anzahl der Elemente in der ElementList zurück.

**Returns:**
int-Wert

### item {#item-int-}
```
public Element item(int index)
```

Ruft ein Element am angegebenen Index ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  |  |

**Returns:**
Das /Aspose.Pdf.LogicalStructure.Element mit dem angegebenen Index in der Sammlung. Wenn der Index größer oder gleich der Anzahl der Elemente in der Liste ist, wird null zurückgegeben.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Gibt einen Enumerator zurück, der die Sammlung von Elementen durchläuft.

**Returns:**
Ein Enumerator, der verwendet wird, um die Sammlung von Elementen zu durchlaufen.
