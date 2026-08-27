---
title: "عنصر"
linktitle: "عنصر"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة أساسية للعنصر في البنية المنطقية."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

يمثل فئة أساسية للعنصر في البنية المنطقية.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | أضف {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | أضف {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال. |
| [clearChilds](#clearChilds--) | امسح جميع العناصر الفرعية. |
| [findElements](#findElements-java.lang.Class-) | ابحث عن العناصر من نوع معين |
| [findElements](#findElements-java.lang.Class-boolean-) | ابحث عن العناصر من نوع معين |
| [getChildElements](#getChildElements--) | يحصل على مجموعة الأطفال لكائنات {@code Element}. |
| [getElementEngine](#getElementEngine--) | احصل على العنصر الأب. |
| [getParentElement](#getParentElement--) | يحصل على مجموعة الأب لكائنات {@code Element}. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | طريقة داخلية |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | أدرج {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال عند الفهرس المحدد. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | أدرج {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال عند الفهرس المحدد. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | أزل العنصر الفرعي عند. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | ربط عنصر بنية بالتعليق التوضيحي. |
| [tag](#tag-com.aspose.pdf.Artifact-) | ربط عنصر بنية بالقطعة. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | ربط عنصر بنية بمشغل BDC في تدفق المحتوى. |
| [tag](#tag-com.aspose.pdf.XForm-) | ربط عنصر بنية بنموذج XForm في تدفق المحتوى. |
| [tag](#tag-com.aspose.pdf.XImage-) | ربط عنصر بنية بـ XImage. |
| [toString](#toString--) | يعيد سلسلة تمثل الكائن الحالي. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
أضف {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
أضف {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

امسح جميع العناصر الفرعية.

### findElements {#findElements-java.lang.Class-}
ابحث عن العناصر من نوع معين

### findElements {#findElements-java.lang.Class-boolean-}
ابحث عن العناصر من نوع معين

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

يحصل على مجموعة الأطفال لكائنات {@code Element}.

**Returns:**
القيمة: مجموعة الأطفال لكائنات {@code Element}.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

احصل على العنصر الأب.

**Returns:**
القيمة: العنصر الأب.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

يحصل على مجموعة الأب لكائنات {@code Element}.

**Returns:**
القيمة: مجموعة الأب لكائنات {@code Element}.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

طريقة داخلية

**Returns:**
عنصر داخلي

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
أدرج {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال عند الفهرس المحدد.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
أدرج {@code /Aspose.Pdf.LogicalStructure.Element} إلى مجموعة الأطفال عند الفهرس المحدد.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

أزل العنصر الفرعي عند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس العنصر الفرعي. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
ربط عنصر بنية بالتعليق التوضيحي.

### tag {#tag-com.aspose.pdf.Artifact-}
ربط عنصر بنية بالقطعة.

### tag {#tag-com.aspose.pdf.operators.BDC-}
ربط عنصر بنية بمشغل BDC في تدفق المحتوى.

### tag {#tag-com.aspose.pdf.XForm-}
ربط عنصر بنية بنموذج XForm في تدفق المحتوى.

### tag {#tag-com.aspose.pdf.XImage-}
ربط عنصر بنية بـ XImage.

### toString {#toString--}
```
public String toString()
```

يعيد سلسلة تمثل الكائن الحالي.

**Returns:**
سلسلة تمثل الكائن الحالي.
