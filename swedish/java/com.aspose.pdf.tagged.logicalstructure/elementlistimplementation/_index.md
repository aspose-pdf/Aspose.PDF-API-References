---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Aspose.PDF för Java API-referens"
description:
type: docs
weight: 50
url: /sv/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Lägg till element i listan. |
| [getCount](#getCount--) | Hämtar antalet element i ElementList. |
| [item](#item-int-) | Hämtar ett element på det angivna indexet. |
| [iterator](#iterator--) | Hämtar en enumerator som itererar genom samlingen av element. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Lägg till element i listan.

### getCount {#getCount--}
```
public int getCount()
```

Hämtar antalet element i ElementList.

**Returns:**
int‑värde

### item {#item-int-}
```
public Element item(int index)
```

Hämtar ett element på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  |  |

**Returns:**
Den /Aspose.Pdf.LogicalStructure.Element med det angivna indexet i samlingen. Om index är större än eller lika med antalet element i listan returneras null.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Hämtar en enumerator som itererar genom samlingen av element.

**Returns:**
En enumerator som används för att iterera genom samlingen av element.
