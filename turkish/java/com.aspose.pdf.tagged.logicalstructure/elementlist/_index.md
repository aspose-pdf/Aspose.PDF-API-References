---
title: "ElementList"
linktitle: "ElementList"
second_title: "Aspose.PDF for Java API Referansı"
description: "Öğelerin sıralı bir koleksiyonunu temsil eder."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Öğelerin sıralı bir koleksiyonunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Listeye öğe ekle. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | ElementList içindeki öğe sayısını alır. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Listeye öğe ekleyin. |
| [item](#item-int-) | Verilen indeksteki bir öğeyi alır. |
| [iterator](#iterator--) | Öğeler koleksiyonunda dolaşan bir enumerator alır. |
| [removeAt](#removeAt-int-) | Listedeki öğeyi kaldırın. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Listedeki öğeyi kaldırın. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Listeye öğe ekle.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

ElementList içindeki öğe sayısını alır.

**Returns:**
int değer

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Listeye öğe ekleyin.

### item {#item-int-}
```
public abstract Element item(int index)
```

Verilen indeksteki bir öğeyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Öğeler listesindeki indeks. |

**Returns:**
Koleksiyondaki belirtilen indeksli {@code /Aspose.Pdf.LogicalStructure.Element}. {@code index} listedeki öğe sayısına eşit ya da daha büyükse, bu null döndürür.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Öğeler koleksiyonunda dolaşan bir enumerator alır.

**Returns:**
Öğeler koleksiyonunda dolaşmak için kullanılan bir enumerator.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Listedeki öğeyi kaldırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Kaldırılacak indeks. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Listedeki öğeyi kaldırın.
