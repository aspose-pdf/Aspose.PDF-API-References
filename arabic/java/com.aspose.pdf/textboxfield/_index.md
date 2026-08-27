---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل حقل صندوق النص."
type: docs
weight: 4930
url: /ar/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

فئة تمثل حقل صندوق النص.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextBoxField](#TextBoxField--) | إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc) |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | يضيف barcode 128 إلى الحقل. سيتم تغيير قيمة الحقل إلى الشيفرة وسيصبح الحقل للقراءة فقط. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | يضيف صورة إلى موارد الحقل ويرسمها. |
| [getForceCombs](#getForceCombs--) | يحصل على العلامة التي تشير إلى ما إذا كان الحقل مقسَّماً إلى مواضع متباعدة. |
| [getMaxLen](#getMaxLen--) | يحصل على الحد الأقصى لطول النص في الحقل. |
| [getMultiline](#getMultiline--) | يحصل على علامة تعدد الأسطر في الحقل. إذا كان Multiline صحيحًا، يمكن للحقل أن يحتوي على عدة أسطر من النص. |
| [getScrollable](#getScrollable--) | يحصل على علامة القابلية للتمرير في الحقل. إذا كانت true، يمكن تمرير الحقل. |
| [getSpellCheck](#getSpellCheck--) | يحصل على علامة التدقيق الإملائي للحقل. إذا كانت true، سيُجرى تدقيق إملائي للحقل. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | يحصل أو يضبط محاذاة النص العمودية للتعليق. |
| [getValue](#getValue--) | يحصل على قيمة الحقل. |
| [setForceCombs](#setForceCombs-boolean-) | يضبط العلامة التي تشير إلى ما إذا كان الحقل مقسماً إلى مواضع متباعدة. |
| [setJustification](#setJustification-boolean-) | يضبط المحاذاة |
| [setMaxLen](#setMaxLen-int-) | يضبط الحد الأقصى لطول النص في الحقل. |
| [setMultiline](#setMultiline-boolean-) | يضبط علامة تعدد الأسطر للحقل. إذا كان Multiline صحيحًا يمكن للحقل أن يحتوي على عدة أسطر من النص. |
| [setScrollable](#setScrollable-boolean-) | يضبط علامة القابلية للتمرير للحقل. إذا كان صحيحًا يمكن تمرير الحقل. |
| [setSpellCheck](#setSpellCheck-boolean-) | يضبط علامة التدقيق الإملائي للحقل. إذا كان صحيحًا سيتم تدقيق إملاء الحقل. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يحصل أو يضبط محاذاة النص العمودية للتعليق. |
| [setValue](#setValue-java.lang.String-) | يضبط قيمة الحقل. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
إنشاء نسخة من TextBoxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
يضيف barcode 128 إلى الحقل. سيتم تغيير قيمة الحقل إلى الشيفرة وسيصبح الحقل للقراءة فقط.

### addImage {#addImage-java.awt.image.BufferedImage-}
يضيف صورة إلى موارد الحقل ويرسمها.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

يحصل على العلامة التي تشير إلى ما إذا كان الحقل مقسَّماً إلى مواضع متباعدة.

**Returns:**
قيمة منطقية

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

يحصل على الحد الأقصى لطول النص في الحقل.

**Returns:**
قيمة int

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

يحصل على علامة تعدد الأسطر في الحقل. إذا كان Multiline صحيحًا، يمكن للحقل أن يحتوي على عدة أسطر من النص.

**Returns:**
قيمة منطقية

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

يحصل على علامة القابلية للتمرير في الحقل. إذا كانت true، يمكن تمرير الحقل.

**Returns:**
قيمة منطقية

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

يحصل على علامة التدقيق الإملائي للحقل. إذا كانت true، سيُجرى تدقيق إملائي للحقل.

**Returns:**
قيمة منطقية

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

يحصل أو يضبط محاذاة النص العمودية للتعليق.

**Returns:**
عنصر VerticalAlignment

### getValue {#getValue--}
```
public String getValue()
```

يحصل على قيمة الحقل.

**Returns:**
قيمة سلسلة

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

يضبط العلامة التي تشير إلى ما إذا كان الحقل مقسماً إلى مواضع متباعدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

يضبط المحاذاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

يضبط الحد الأقصى لطول النص في الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

يضبط علامة تعدد الأسطر للحقل. إذا كان Multiline صحيحًا يمكن للحقل أن يحتوي على عدة أسطر من النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

يضبط علامة القابلية للتمرير للحقل. إذا كان صحيحًا يمكن تمرير الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

يضبط علامة التدقيق الإملائي للحقل. إذا كان صحيحًا سيتم تدقيق إملاء الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يحصل أو يضبط محاذاة النص العمودية للتعليق.

### setValue {#setValue-java.lang.String-}
يضبط قيمة الحقل.
