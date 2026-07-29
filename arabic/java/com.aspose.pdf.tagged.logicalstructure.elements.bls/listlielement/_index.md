---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل عنصر بنية LI في البنية المنطقية للقائمة."
type: docs
weight: 110
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

يمثل عنصر بنية LI في البنية المنطقية للقائمة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | يضيف مرجعًا إلى {@link StructureElement} المحدد داخل عنصر جدول المحتويات (TOCI) هذا. يُستخدم عادةً عندما يكون {@code ListLIElement} عنوانًا لجدول المحتويات في جداول المحتويات المتداخلة. |
| [getGetElement](#getGetElement--) | يحصل على عنصر PDF الأساسي الذي يمثل بنية TOCI هذه. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
يضيف مرجعًا إلى {@link StructureElement} المحدد داخل عنصر جدول المحتويات (TOCI) هذا. يُستخدم عادةً عندما يكون {@code ListLIElement} عنوانًا لجدول المحتويات في جداول المحتويات المتداخلة.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

يحصل على عنصر PDF الأساسي الذي يمثل بنية TOCI هذه.

**Returns:**
العنصر الذي يُشكل التمثيل الهيكلي لهذا مدخل جدول المحتويات.

### preSave {#preSave--}
```
public void preSave()
```
