---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "مجموعة صفحات وثيقة PDF."
type: docs
weight: 3340
url: /ar/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

مجموعة صفحات وثيقة PDF.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر {@code AnnotationSelector} الذي يوفر وظيفة للعمل مع التعليقات التوضيحية. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | يقبل كائن الزائر {@code ImagePlacementAbsorber} الذي يوفر وظيفة للعمل مع كائنات وضع الصور. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | يقبل كائن الزائر {@code TextAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | يقبل كائن الزائر {@code TextFragmentAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | يضيف صفحة إلى المجموعة. |
| [add](#add--) | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [add](#add-java.lang.Iterable-) | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [add](#add-java.util.List-) | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [add](#add-com.aspose.pdf.Page-) | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [add](#add-com.aspose.pdf.Page:A-) | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [beginUpdate](#beginUpdate--) | يُحدّث عندما تبدأ تغييرات المجموعة. |
| [clear](#clear--) | يمسح مجموعة الصفحات. |
| [contains](#contains-com.aspose.pdf.Page-) | يحدد ما إذا كان هذا المثيل يحتوي على الكائن. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | ينسخ الصفحات إلى المستند. |
| [delete](#delete--) | يحذف جميع الصفحات من المجموعة. |
| [delete](#delete-int-) | احذف الصفحة المحددة. |
| [delete](#delete-java.lang.Integer:A-) | يحذف جميع الصفحات من المجموعة. |
| [endUpdate](#endUpdate--) | يُحدّث عندما تكتمل تغييرات المجموعة. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | يزيل جميع الحقول الموجودة على الصفحات ويضع قيمها بدلاً منها. |
| [freeMemory](#freeMemory--) | يمسح البيانات المخزنة مؤقتًا |
| [get_Item](#get_Item-int-) | يحصل على الصفحة حسب الفهرس. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن المزامنة للمجموعة. |
| [getUnrestricted](#getUnrestricted-int-) | يرجع الصفحة حسب فهرسها. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> يرجع فهرس الصفحة المحددة. </p> |
| [insert](#insert-int-) | يدرج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [insert](#insert-int-java.lang.Iterable-) | يدرج الصفحات من المجموعة إلى المستند. |
| [insert](#insert-int-java.util.List-) | يدرج الصفحات من المجموعة إلى المستند. |
| [insert](#insert-int-com.aspose.pdf.Page-) | يدرج صفحة في مجموعة الصفحات في المكان المحدد. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | يدرج صفحات المصفوفة إلى المستند. |
| [isEmpty](#isEmpty--) | يرجع TRUE إذا كانت المجموعة فارغة. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى أن المجموعة للقراءة فقط. دائمًا يرجع false. |
| [isSynchronized](#isSynchronized--) | يرجع true إذا كان الكائن متزامنًا. |
| [iterator](#iterator--) | يرجع عداد الصفحات. |
| [remove](#remove-com.aspose.pdf.Page-) | يزيل العنصر المحدد، ويرمي استثناء. |
| [size](#size--) | يحصل على عدد الصفحات في المستند. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر {@code AnnotationSelector} الذي يوفر وظيفة للعمل مع التعليقات التوضيحية.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
يقبل كائن الزائر {@code ImagePlacementAbsorber} الذي يوفر وظيفة للعمل مع كائنات وضع الصور.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
يقبل كائن الزائر {@code TextAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
يقبل كائن الزائر {@code TextFragmentAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
يضيف صفحة إلى المجموعة.

### add {#add--}
```
public Page add()
```

يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

**Returns:**
تمت إضافة الصفحة.

### add {#add-java.lang.Iterable-}
يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

**Returns:**
تمت إضافة الصفحة.

### add {#add-java.util.List-}
يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

**Returns:**
تمت إضافة الصفحة.

### add {#add-com.aspose.pdf.Page-}
يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

**Returns:**
تمت إضافة الصفحة.

### add {#add-com.aspose.pdf.Page:A-}
يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

**Returns:**
تمت إضافة الصفحة.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

يُحدّث عندما تبدأ تغييرات المجموعة.

### clear {#clear--}
```
public void clear()
```

يمسح مجموعة الصفحات.

### contains {#contains-com.aspose.pdf.Page-}
يحدد ما إذا كان هذا المثيل يحتوي على الكائن.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
ينسخ الصفحات إلى المستند.

### delete {#delete--}
```
public void delete()
```

يحذف جميع الصفحات من المجموعة.

### delete {#delete-int-}
```
public void delete(int index)
```

احذف الصفحة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | رقم الصفحة التي سيتم حذفها. أرقام الصفحات تبدأ من 1. |

### delete {#delete-java.lang.Integer:A-}
يحذف جميع الصفحات من المجموعة.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

يُحدّث عندما تكتمل تغييرات المجموعة.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

يزيل جميع الحقول الموجودة على الصفحات ويضع قيمها بدلاً منها.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

يمسح البيانات المخزنة مؤقتًا

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

يحصل على الصفحة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الصفحة. |

**Returns:**
تم استرجاع الصفحة.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن المزامنة للمجموعة.

**Returns:**
كائن للمزامنة

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

يرجع الصفحة حسب فهرسها. {@code Page}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الصفحة المطلوبة. الصفحات مرقمة من 1. |

**Returns:**
الصفحة المطلوبة

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> يرجع فهرس الصفحة المحددة. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

يدرج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | موضع الصفحة الجديدة. |

**Returns:**
تم إدراج الصفحة.

### insert {#insert-int-java.lang.Iterable-}
يدرج الصفحات من المجموعة إلى المستند.

### insert {#insert-int-java.util.List-}
يدرج الصفحات من المجموعة إلى المستند.

### insert {#insert-int-com.aspose.pdf.Page-}
يدرج صفحة في مجموعة الصفحات في المكان المحدد.

### insert {#insert-int-com.aspose.pdf.Page:A-}
يدرج صفحات المصفوفة إلى المستند.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

يرجع TRUE إذا كانت المجموعة فارغة.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى أن المجموعة للقراءة فقط. دائمًا يرجع false.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يرجع true إذا كان الكائن متزامنًا.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

يرجع عداد الصفحات.

**Returns:**
عداد الصفحات

### remove {#remove-com.aspose.pdf.Page-}
يزيل العنصر المحدد، ويرمي استثناء.

### size {#size--}
```
public int size()
```

يحصل على عدد الصفحات في المستند.

**Returns:**
قيمة int
