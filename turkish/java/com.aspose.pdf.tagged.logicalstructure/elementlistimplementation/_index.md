---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Aspose.PDF for Java API Referansı"
description:
type: docs
weight: 50
url: /tr/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Listeye öğe ekle. |
| [getCount](#getCount--) | ElementList içindeki öğe sayısını alır. |
| [item](#item-int-) | Verilen indeksteki bir öğeyi alır. |
| [iterator](#iterator--) | Öğeler koleksiyonunda dolaşan bir enumerator alır. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Listeye öğe ekle.

### getCount {#getCount--}
```
public int getCount()
```

ElementList içindeki öğe sayısını alır.

**Returns:**
int değer

### item {#item-int-}
```
public Element item(int index)
```

Verilen indeksteki bir öğeyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  |  |

**Returns:**
Koleksiyondaki belirtilen indekse sahip /Aspose.Pdf.LogicalStructure.Element. Eğer indeks, listedeki öğe sayısına eşit ya da daha büyükse, bu null döndürür.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Öğeler koleksiyonunda dolaşan bir enumerator alır.

**Returns:**
Öğeler koleksiyonunda dolaşmak için kullanılan bir enumerator.
