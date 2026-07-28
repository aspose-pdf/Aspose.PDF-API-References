---
title: "ElementList"
linktitle: "ElementList"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en ordnad samling av element."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Representerar en ordnad samling av element.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Lägg till element i listan. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Hämtar antalet element i ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Infoga element i listan. |
| [item](#item-int-) | Hämtar ett element på det angivna indexet. |
| [iterator](#iterator--) | Hämtar en enumerator som itererar genom samlingen av element. |
| [removeAt](#removeAt-int-) | Ta bort element från listan. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Ta bort element från listan. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Lägg till element i listan.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet element i ElementList.

**Returns:**
int‑värde

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Infoga element i listan.

### item {#item-int-}
```
public abstract Element item(int index)
```

Hämtar ett element på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Indexet i listan med element. |

**Returns:**
Den {@code /Aspose.Pdf.LogicalStructure.Element} med det angivna indexet i samlingen. Om {@code index} är större än eller lika med antalet element i listan, returneras null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Hämtar en enumerator som itererar genom samlingen av element.

**Returns:**
En enumerator som används för att iterera genom samlingen av element.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Ta bort element från listan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index att ta bort. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Ta bort element från listan.
