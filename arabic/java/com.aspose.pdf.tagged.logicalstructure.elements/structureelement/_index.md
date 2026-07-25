---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة أساسية لعناصر البنية في البنية المنطقية."
type: docs
weight: 110
url: /ar/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

يمثل فئة أساسية لعناصر البنية في البنية المنطقية.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | تغيير العنصر الأب للعنصر الهيكلي الحالي |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | تغيير العنصر الأب للعنصر الهيكلي الحالي |
| [clearId](#clearId--) | مسح المعرف للعنصر الهيكلي. |
| [generateId](#generateId--) | إنشاء معرف للعنصر الهيكلي. |
| [getActualText](#getActualText--) | يحصل أو يضبط النص الفعلي للعنصر الهيكلي. |
| [getAlternativeText](#getAlternativeText--) | يحصل أو يضبط النص البديل للعنصر الهيكلي. |
| [getAttributes](#getAttributes--) | يحصل على كائن {@code StructureAttributeCollection}. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | يحصل على كائن {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. القيمة: كائن {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. |
| [getExpansionText](#getExpansionText--) | يحصل أو يضبط نص التوسيع للعنصر الهيكلي. |
| [getID](#getID--) | يحصل على المعرف للعنصر الهيكلي. القيمة: معرف العنصر الهيكلي. |
| [getLanguage](#getLanguage--) | يحصل أو يضبط اللغة للعنصر الهيكلي. |
| [getPage](#getPage--) | يحصل على الصفحة التي سيتم فيها عرض بعض أو كل العناصر الفرعية. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | يحصل على نوع العنصر الهيكلي. |
| [getTitle](#getTitle--) | يحصل أو يضبط العنوان لعنصر الهيكل. |
| [remove](#remove--) | يزيل: عنصرًا من الهيكل، وإشارةً إليه من الكائن الأب، وإشاراتٍ إليه من الكائنات الفرعية، والكائن المقابل من المستند. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | يزيل عنصرًا من الهيكل، وإشارةً إليه من الكائن الأب، وإشاراتٍ إليه من الكائنات الفرعية، والكائن المقابل من المستند. يُدرج الكائنات الفرعية للعنصر المُزال في مجموعة كائنات الطفل الخاصة بالوالد السابق بدءًا من فهرس العنصر المُزال. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | يزيل عنصرًا من الهيكل، وإشارةً إليه من الكائن الأب، وإشاراتٍ إليه من الكائنات الفرعية، والكائن المقابل من المستند. يُدرج الكائنات الفرعية للعنصر المُزال في مجموعة كائنات الطفل الخاصة بالوالد السابق بدءًا من فهرس العنصر المُزال. |
| [setActualText](#setActualText-java.lang.String-) | يحصل أو يضبط النص الفعلي للعنصر الهيكلي. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | يحصل أو يضبط النص البديل للعنصر الهيكلي. |
| [setExpansionText](#setExpansionText-java.lang.String-) | يحصل أو يضبط نص التوسيع للعنصر الهيكلي. |
| [setId](#setId-java.lang.String-) | يضبط المعرف لعنصر الهيكل. |
| [setLanguage](#setLanguage-java.lang.String-) | يحصل أو يضبط اللغة للعنصر الهيكلي. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | تعيين عنصر الأب |
| [setTag](#setTag-java.lang.String-) | يضبط العلامة المخصصة لعنصر الهيكل. |
| [setTitle](#setTitle-java.lang.String-) | يحصل أو يضبط العنوان لعنصر الهيكل. |
| [tag](#tag-com.aspose.pdf.Annotation-) | ربط عنصر بنية بالتعليق التوضيحي. |
| [tag](#tag-com.aspose.pdf.Artifact-) | ربط عنصر بنية بالقطعة. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | ربط عنصر بنية بمشغل BDC في تدفق المحتوى. |
| [tag](#tag-com.aspose.pdf.XForm-) | ربط عنصر بنية بنموذج XForm في تدفق المحتوى. |
| [tag](#tag-com.aspose.pdf.XImage-) | ربط عنصر بنية بـ XImage. |
| [toString](#toString--) | يعيد سلسلة تمثل الكائن الحالي. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
تغيير العنصر الأب للعنصر الهيكلي الحالي

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
تغيير العنصر الأب للعنصر الهيكلي الحالي

### clearId {#clearId--}
```
public final void clearId()
```

مسح المعرف للعنصر الهيكلي.

### generateId {#generateId--}
```
public final void generateId()
```

إنشاء معرف للعنصر الهيكلي.

### getActualText {#getActualText--}
```
public final String getActualText()
```

يحصل أو يضبط النص الفعلي للعنصر الهيكلي.

**Returns:**
القيمة: النص الفعلي لعنصر الهيكل.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

يحصل أو يضبط النص البديل للعنصر الهيكلي.

**Returns:**
القيمة: النص البديل لعنصر الهيكل.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

يحصل على كائن {@code StructureAttributeCollection}.

**Returns:**
كائن {@code StructureAttributeCollection}.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

يحصل على كائن {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. القيمة: كائن {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}.

**Returns:**
مثيل AttributeOwnerStandard

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

يحصل أو يضبط نص التوسيع للعنصر الهيكلي.

**Returns:**
القيمة: نص التوسيع لعنصر الهيكل.

### getID {#getID--}
```
public final String getID()
```

يحصل على المعرف للعنصر الهيكلي. القيمة: معرف العنصر الهيكلي.

**Returns:**
قيمة سلسلة

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

يحصل أو يضبط اللغة للعنصر الهيكلي.

**Returns:**
القيمة: لغة عنصر الهيكل.

### getPage {#getPage--}
```
public final Page getPage()
```

يحصل على الصفحة التي سيتم فيها عرض بعض أو كل العناصر الفرعية.

**Returns:**
كائن الصفحة

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

يحصل على نوع العنصر الهيكلي.

**Returns:**
القيمة: كائن {@code StructureTypeStandard} لعنصر الهيكل.

### getTitle {#getTitle--}
```
public final String getTitle()
```

يحصل أو يضبط العنوان لعنصر الهيكل.

**Returns:**
القيمة: عنوان عنصر الهيكل.

### remove {#remove--}
```
public final void remove()
```

يزيل: عنصرًا من الهيكل، وإشارةً إليه من الكائن الأب، وإشاراتٍ إليه من الكائنات الفرعية، والكائن المقابل من المستند.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

يزيل عنصرًا من الهيكل، وإشارةً إليه من الكائن الأب، وإشاراتٍ إليه من الكائنات الفرعية، والكائن المقابل من المستند. يُدرج الكائنات الفرعية للعنصر المُزال في مجموعة كائنات الطفل الخاصة بالوالد السابق بدءًا من فهرس العنصر المُزال.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

يزيل عنصرًا من الهيكل، وإشارةً إليه من الكائن الأب، وإشاراتٍ إليه من الكائنات الفرعية، والكائن المقابل من المستند. يُدرج الكائنات الفرعية للعنصر المُزال في مجموعة كائنات الطفل الخاصة بالوالد السابق بدءًا من فهرس العنصر المُزال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | تحقق مما إذا كان يمكن إدراج الكائنات الفرعية للعنصر المُزال في مجموعة كائنات الطفل الخاصة بالوالد. |

### setActualText {#setActualText-java.lang.String-}
يحصل أو يضبط النص الفعلي للعنصر الهيكلي.

### setAlternativeText {#setAlternativeText-java.lang.String-}
يحصل أو يضبط النص البديل للعنصر الهيكلي.

### setExpansionText {#setExpansionText-java.lang.String-}
يحصل أو يضبط نص التوسيع للعنصر الهيكلي.

### setId {#setId-java.lang.String-}
يضبط المعرف لعنصر الهيكل.

### setLanguage {#setLanguage-java.lang.String-}
يحصل أو يضبط اللغة للعنصر الهيكلي.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
تعيين عنصر الأب

### setTag {#setTag-java.lang.String-}
يضبط العلامة المخصصة لعنصر الهيكل.

### setTitle {#setTitle-java.lang.String-}
يحصل أو يضبط العنوان لعنصر الهيكل.

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
