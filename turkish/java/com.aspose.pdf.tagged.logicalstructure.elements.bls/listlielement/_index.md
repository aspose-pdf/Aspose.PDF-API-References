---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Listenin mantıksal yapısında LI yapı öğesini temsil eder."
type: docs
weight: 110
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Listenin mantıksal yapısında LI yapı öğesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Bu İçindekiler Tablosu Öğesi (TOCI) öğesi içinde belirtilen {@link StructureElement} öğesine bir referans ekler. Bu genellikle {@code ListLIElement} iç içe geçmiş içerik tablolarında TOC başlığı olarak hizmet ettiğinde kullanılır. |
| [getGetElement](#getGetElement--) | Bu TOCI yapısını temsil eden temel PDF öğesini alır. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Bu İçindekiler Tablosu Öğesi (TOCI) öğesi içinde belirtilen {@link StructureElement} öğesine bir referans ekler. Bu genellikle {@code ListLIElement} iç içe geçmiş içerik tablolarında TOC başlığı olarak hizmet ettiğinde kullanılır.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Bu TOCI yapısını temsil eden temel PDF öğesini alır.

**Returns:**
Bu içindekiler tablosu girişinin yapısal temsilini oluşturan Element.

### preSave {#preSave--}
```
public void preSave()
```
