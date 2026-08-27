---
title: "حقل"
linktitle: "حقل"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة الأساسية لحقول النموذج Acro."
type: docs
weight: 1380
url: /ar/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

الفئة الأساسية لحقول النموذج Acro.

## الحقول

| حقل | الوصف |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | إنشاء حقل للاستخدام في Generator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | نسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | نسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | تنفيذ إجراء JavaScript محدد لهذا الحقل. |
| [flatten](#flatten--) | إزالة هذا الحقل ووضع قيمته مباشرةً على الصفحة. |
| [get_Item](#get_Item-int-) | الحصول على الحقل الفرعي الموجود في هذا الحقل حسب الفهرس. |
| [get_Item](#get_Item-java.lang.String-) | الحصول على الحقل الفرعي الموجود في هذا الحقل حسب اسم الحقل الفرعي. |
| [getAlternateName](#getAlternateName--) | الحصول على الاسم البديل للحقل (اسم حقل بديل يُستخدم بدلاً من اسم الحقل الفعلي حيثما يتم التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقل في Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | الحصول على فهرس هذه التعليقة على الصفحة. |
| [getMappingName](#getMappingName--) | الحصول على اسم التعيين للحقل الذي سيُستخدم عند تصدير بيانات نماذج الحقول التفاعلية من المستند. |
| [getMaxFontSize](#getMaxFontSize--) | الحد الأقصى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم. |
| [getMinFontSize](#getMinFontSize--) | الحد الأدنى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم. |
| [getPageIndex](#getPageIndex--) | الحصول على فهرس الصفحة التي تحتوي على هذا الحقل. |
| [getPartialName](#getPartialName--) | الحصول على الاسم الجزئي للحقل. |
| [getRect](#getRect--) | الحصول على مستطيل الحقل. |
| [getSyncRoot](#getSyncRoot--) | كائن المزامنة. |
| [getTabOrder](#getTabOrder--) | الحصول على ترتيب التبويب أو تعيينه للحقل. |
| [getValue](#getValue--) | يحصل على قيمة الحقل. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | إذا كان صحيحًا، سيتم تقليل حجم الخط لتناسب النص داخل المستطيل المحدد. |
| [isGroup](#isGroup--) | الحصول على القيمة المنطقية التي تشير إلى ما إذا كان هذا الحقل حقلًا غير نهائي أي مجموعة من الحقول. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | خاصية لدعم Generator. تُستخدم عندما يُضاف الحقل إلى الرأس أو التذييل. إذا كان صحيحًا، سيتم إنشاء هذا الحقل مرة واحدة وستكون مظهره مرئيًا على جميع صفحات المستند. إذا كان خاطئًا، سيتم إنشاء حقل منفصل لكل صفحة من المستند. |
| [isSynchronized](#isSynchronized--) | إرجاع true إذا كان القاموس متزامنًا. |
| [iterator](#iterator--) | إرجاع عداد للحقول المحتواة. |
| [recalculate](#recalculate--) | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | يضبط الاسم البديل للحقول (اسم حقل بديل يُستخدم بدلاً من اسم الحقل الفعلي حيثما يتم التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقول في Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | يضبط فهرس هذه التعليقة على الصفحة. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | إذا كان صحيحًا، سيتم تقليل حجم الخط لتناسب النص داخل المستطيل المحدد. |
| [setMappingName](#setMappingName-java.lang.String-) | يضبط اسم التعيين للحقول الذي سيُستخدم عند تصدير بيانات حقول النموذج التفاعلية من المستند. |
| [setMaxFontSize](#setMaxFontSize-double-) | الحد الأقصى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم. |
| [setMinFontSize](#setMinFontSize-double-) | الحد الأدنى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم. |
| [setPartialName](#setPartialName-java.lang.String-) | يضبط الاسم الجزئي للحقول. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | اضبط موضع الحقل. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | يضبط مستطيل الحقل. |
| [setSharedField](#setSharedField-boolean-) | خاصية لدعم Generator. تُستخدم عندما يُضاف الحقل إلى الرأس أو التذييل. إذا كان صحيحًا، سيتم إنشاء هذا الحقل مرة واحدة وستكون مظهره مرئيًا على جميع صفحات المستند. إذا كان خاطئًا، سيتم إنشاء حقل منفصل لكل صفحة من المستند. |
| [setTabOrder](#setTabOrder-int-) | الحصول على ترتيب التبويب أو تعيينه للحقل. |
| [setValue](#setValue-java.lang.String-) | اضبط القيمة. |
| [size](#size--) | يحصل على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار). |
| [updateAppearances](#updateAppearances--) | تحديث قيمة المظهر. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
إنشاء حقل للاستخدام في Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
نسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
نسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
تنفيذ إجراء JavaScript محدد لهذا الحقل.

### flatten {#flatten--}
```
public void flatten()
```

إزالة هذا الحقل ووضع قيمته مباشرةً على الصفحة.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

الحصول على الحقل الفرعي الموجود في هذا الحقل حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الحقل الفرعي المطلوب. |

**Returns:**
مثيل الحقل.

### get_Item {#get_Item-java.lang.String-}
الحصول على الحقل الفرعي الموجود في هذا الحقل حسب اسم الحقل الفرعي.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

الحصول على الاسم البديل للحقل (اسم حقل بديل يُستخدم بدلاً من اسم الحقل الفعلي حيثما يتم التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقل في Adobe Acrobat.

**Returns:**
قيمة سلسلة

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

الحصول على فهرس هذه التعليقة على الصفحة.

**Returns:**
قيمة int

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

الحصول على اسم التعيين للحقل الذي سيُستخدم عند تصدير بيانات نماذج الحقول التفاعلية من المستند.

**Returns:**
قيمة سلسلة

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

الحد الأقصى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم.

**Returns:**
قيمة double

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

الحد الأدنى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم.

**Returns:**
قيمة double

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

الحصول على فهرس الصفحة التي تحتوي على هذا الحقل.

**Returns:**
قيمة int

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

الحصول على الاسم الجزئي للحقل.

**Returns:**
قيمة سلسلة

### getRect {#getRect--}
```
public Rectangle getRect()
```

الحصول على مستطيل الحقل.

**Returns:**
مستطيل الحقل.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

كائن المزامنة.

**Returns:**
قيمة الكائن

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

الحصول على ترتيب التبويب أو تعيينه للحقل.

**Returns:**
قيمة int

### getValue {#getValue--}
```
public String getValue()
```

يحصل على قيمة الحقل.

**Returns:**
قيمة سلسلة

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

إذا كان صحيحًا، سيتم تقليل حجم الخط لتناسب النص داخل المستطيل المحدد.

**Returns:**
قيمة منطقية

### isGroup {#isGroup--}
```
public boolean isGroup()
```

الحصول على القيمة المنطقية التي تشير إلى ما إذا كان هذا الحقل حقلًا غير نهائي أي مجموعة من الحقول.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

خاصية لدعم Generator. تُستخدم عندما يُضاف الحقل إلى الرأس أو التذييل. إذا كان صحيحًا، سيتم إنشاء هذا الحقل مرة واحدة وستكون مظهره مرئيًا على جميع صفحات المستند. إذا كان خاطئًا، سيتم إنشاء حقل منفصل لكل صفحة من المستند.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

إرجاع true إذا كان القاموس متزامنًا.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

إرجاع عداد للحقول المحتواة.

**Returns:**
كائن عدّاد.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

يعيد حساب جميع الحقول المحسوبة في النموذج.

**Returns:**
صحيح إذا تم تغيير قيمة الحقل أثناء إعادة الحساب.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
يضبط الاسم البديل للحقول (اسم حقل بديل يُستخدم بدلاً من اسم الحقل الفعلي حيثما يتم التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقول في Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

يضبط فهرس هذه التعليقة على الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

إذا كان صحيحًا، سيتم تقليل حجم الخط لتناسب النص داخل المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMappingName {#setMappingName-java.lang.String-}
يضبط اسم التعيين للحقول الذي سيُستخدم عند تصدير بيانات حقول النموذج التفاعلية من المستند.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

الحد الأقصى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

الحد الأدنى لحجم الخط الذي يمكن استخدامه لمحتويات الحقل. -1 لعدم فحص الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setPartialName {#setPartialName-java.lang.String-}
يضبط الاسم الجزئي للحقول.

### setPosition {#setPosition-com.aspose.pdf.Point-}
اضبط موضع الحقل.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
يضبط مستطيل الحقل.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

خاصية لدعم Generator. تُستخدم عندما يُضاف الحقل إلى الرأس أو التذييل. إذا كان صحيحًا، سيتم إنشاء هذا الحقل مرة واحدة وستكون مظهره مرئيًا على جميع صفحات المستند. إذا كان خاطئًا، سيتم إنشاء حقل منفصل لكل صفحة من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

الحصول على ترتيب التبويب أو تعيينه للحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setValue {#setValue-java.lang.String-}
اضبط القيمة.

### size {#size--}
```
public int size()
```

يحصل على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار).

**Returns:**
قيمة int

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

تحديث قيمة المظهر.
