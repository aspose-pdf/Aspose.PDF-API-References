---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة مجردة تمثل توضيح العلامة."
type: docs
weight: 2870
url: /ar/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

فئة مجردة تمثل توضيح العلامة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | منشئ |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [clearState](#clearState--) | يمسح الحالة ونموذج الحالة للتعليق. على سبيل المثال، يمسح حالة المراجعة لتعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel. |
| [getCreationDate](#getCreationDate--) | يحصل على التاريخ والوقت عندما تم إنشاء التعليق. |
| [getInReplyTo](#getInReplyTo--) | إشارة إلى التعليق الذي يكون هذا التعليق "in reply to". يجب أن يكون كلا التعليقين على نفس صفحة المستند. |
| [getOpacity](#getOpacity--) | يحصل على قيمة الشفافية الثابتة المستخدمة في رسم التعليق. |
| [getPopup](#getPopup--) | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| [getReplyType](#getReplyType--) | سلسلة تحدد العلاقة (الـ "reply type") بين هذا التعليق وآخر محدد بواسطة InReplyTo. |
| [getRichText](#getRichText--) | يحصل على سلسلة نصية غنية تُعرض في النافذة المنبثقة عند فتح التعليق. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | يحصل على سلسلة نصية غنية تُعرض في النافذة المنبثقة عند فتح التعليق. |
| [getState](#getState--) | يحصل على حالة التعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel. |
| [getStateModel](#getStateModel--) | يحصل على نموذج حالة التعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel. |
| [getSubject](#getSubject--) | يحصل على نص يمثل وصف الكائن. |
| [getTitle](#getTitle--) | يحصل على تسمية نصية تُعرض في شريط عنوان نافذة التعليقпїЅs المنبثقة عند الفتح والنشاط. هذا الإدخال يحدد المستخدم الذي أضاف التعليق. |
| [setCreationDate](#setCreationDate-java.util.Date-) | يحصل على التاريخ والوقت عندما تم إنشاء التعليق. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | إشارة إلى التعليق الذي يكون هذا التعليق "in reply to". يجب أن يكون كلا التعليقين على نفس صفحة المستند. |
| [setMarkedState](#setMarkedState-boolean-) | يضبط الحالة المعلّمة وغير المعلّمة للتعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel. |
| [setOpacity](#setOpacity-double-) | يضبط قيمة الشفافية الثابتة المستخدمة في رسم التعليق. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | سلسلة تحدد العلاقة (الـ "reply type") بين هذا التعليق وآخر محدد بواسطة InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | يضبط حالة المراجعة لتعليق. يتم تجاهل الحالات المعلّمة وغير المعلّمة لأنها لا تنتمي إلى Review StateModel. يتم تعيين الحالة بواسطة المستخدم الذي أنشأ التعليق المستهدف. تُؤخذ القيمة من خاصية Title للتعليق المستهدف. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | يضبط حالة المراجعة لتعليق. يتم تجاهل الحالات المعلّمة وغير المعلّمة لأنها لا تنتمي إلى Review StateModel. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel. |
| [setRichText](#setRichText-java.lang.String-) | يضبط سلسلة نصية غنية تُعرض في النافذة المنبثقة عند فتح التعليق. |
| [setSubject](#setSubject-java.lang.String-) | يضبط نصًا يمثل وصف الكائن. |
| [setTitle](#setTitle-java.lang.String-) | يضبط تسمية نصية تُعرض في شريط عنوان نافذة التعليقпїЅs المنبثقة عند الفتح والنشاط. هذا الإدخال يحدد المستخدم الذي أضاف التعليق. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

منشئ

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
منشئ

### clearState {#clearState--}
```
public final void clearState()
```

يمسح الحالة ونموذج الحالة للتعليق. على سبيل المثال، يمسح حالة المراجعة لتعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

يحصل على التاريخ والوقت عندما تم إنشاء التعليق.

**Returns:**
كائن Date

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

إشارة إلى التعليق الذي يكون هذا التعليق "in reply to". يجب أن يكون كلا التعليقين على نفس صفحة المستند.

**Returns:**
قيمة التعليق

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

يحصل على قيمة الشفافية الثابتة المستخدمة في رسم التعليق.

**Returns:**
قيمة double

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق.

**Returns:**
قيمة PopupAnnotation

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

سلسلة تحدد العلاقة (الـ "reply type") بين هذا التعليق وآخر محدد بواسطة InReplyTo.

**Returns:**
قيمة ReplyType @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

يحصل على سلسلة نصية غنية تُعرض في النافذة المنبثقة عند فتح التعليق.

**Returns:**
قيمة سلسلة

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
يحصل على سلسلة نصية غنية تُعرض في النافذة المنبثقة عند فتح التعليق.

**Returns:**
قيمة سلسلة

### getState {#getState--}
```
public final AnnotationState getState()
```

يحصل على حالة التعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel.

**Returns:**
حالة التعليق.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

يحصل على نموذج حالة التعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel.

**Returns:**
نموذج حالة التعليق.

### getSubject {#getSubject--}
```
public String getSubject()
```

يحصل على نص يمثل وصف الكائن.

**Returns:**
قيمة سلسلة

### getTitle {#getTitle--}
```
public String getTitle()
```

يحصل على تسمية نصية تُعرض في شريط عنوان نافذة التعليقпїЅs المنبثقة عند الفتح والنشاط. هذا الإدخال يحدد المستخدم الذي أضاف التعليق.

**Returns:**
قيمة سلسلة

### setCreationDate {#setCreationDate-java.util.Date-}
يحصل على التاريخ والوقت عندما تم إنشاء التعليق.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
إشارة إلى التعليق الذي يكون هذا التعليق "in reply to". يجب أن يكون كلا التعليقين على نفس صفحة المستند.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

يضبط الحالة المعلّمة وغير المعلّمة للتعليق. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مُعلَّم |  | صحيح إذا تم تعيين الحالة المُعلَّمة، وخطأ إذا تم تعيين الحالة غير المُعلَّمة. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

يضبط قيمة الشفافية الثابتة المستخدمة في رسم التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
سلسلة تحدد العلاقة (الـ "reply type") بين هذا التعليق وآخر محدد بواسطة InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
يضبط حالة المراجعة لتعليق. يتم تجاهل الحالات المعلّمة وغير المعلّمة لأنها لا تنتمي إلى Review StateModel. يتم تعيين الحالة بواسطة المستخدم الذي أنشأ التعليق المستهدف. تُؤخذ القيمة من خاصية Title للتعليق المستهدف. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
يضبط حالة المراجعة لتعليق. يتم تجاهل الحالات المعلّمة وغير المعلّمة لأنها لا تنتمي إلى Review StateModel. ملاحظة، الحالة المخزنة في تعليقات نصية أخرى التي تحتوي على مفاتيح state و statemodel.

### setRichText {#setRichText-java.lang.String-}
يضبط سلسلة نصية غنية تُعرض في النافذة المنبثقة عند فتح التعليق.

### setSubject {#setSubject-java.lang.String-}
يضبط نصًا يمثل وصف الكائن.

### setTitle {#setTitle-java.lang.String-}
يضبط تسمية نصية تُعرض في شريط عنوان نافذة التعليقпїЅs المنبثقة عند الفتح والنشاط. هذا الإدخال يحدد المستخدم الذي أضاف التعليق.
