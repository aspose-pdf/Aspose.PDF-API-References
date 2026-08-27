---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تمثل BoundsCheckableList - غلاف حول System.Collections.Generic.List."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

تمثل BoundsCheckableList - غلاف حول System.Collections.Generic.List.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | تهيئ مثيلاً جديداً من الفئة BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | تهيئ مثيلاً جديداً من الفئة BoundsCheckableList. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addItem](#addItem-T-) | يضيف كائناً إلى نهاية System.Collections.Generic.List اعتماداً على معامل "boundsCheckMode". |
| [clear](#clear--) | يزيل جميع العناصر من System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | يحدد ما إذا كان العنصر موجوداً في System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | ينسخ كامل System.Collections.Generic.List إلى مصفوفة أحادية البعد متوافقة، بدءاً من الفهرس المحدد للمصفوفة الهدف. |
| [get_Item](#get_Item-int-) | يحصل أو يعيّن الفقرة من أو إلى المجموعة. |
| [indexOfItem](#indexOfItem-T-) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأول داخل System.Collections.Generic.List بأكمله. |
| [insertItem](#insertItem-int-T-) | يدرج عنصراً في System.Collections.Generic.List عند الفهرس المحدد. |
| [isReadOnly](#isReadOnly--) | يحصل على القيمة التي تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [iterator](#iterator--) | يعيد عداداً يتنقل عبر System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | يزيل أول ظهور لكائن محدد من System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | يحصل أو يعيّن الفقرة من أو إلى المجموعة. |
| [size](#size--) | يحصل على عدد العناصر الموجودة في System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | يقوم بتحديث معامل boundsCheckMode للمجموعة المُهيأة. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | يقوم بتحديث معامل boundsCheckMode للمجموعة المُهيأة. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

تهيئ مثيلاً جديداً من الفئة BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

تهيئ مثيلاً جديداً من الفئة BoundsCheckableList.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| boundsCheckMode |  | وضع فحص الحدود cCheck. |
| containerWidth |  | عرض الحاوية. |
| containerHeight |  | ارتفاع الحاوية. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

يضيف كائناً إلى نهاية System.Collections.Generic.List اعتماداً على معامل "boundsCheckMode".

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item |  | الكائن الذي سيُضاف إلى نهاية System.Collections.Generic.List. يمكن أن تكون القيمة "null" لأنواع المراجع. |

### clear {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

يحدد ما إذا كان العنصر موجوداً في System.Collections.Generic.List.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item |  | الكائن الذي يُحدد موقعه في System.Collections.Generic.List. يمكن أن تكون القيمة null لأنواع المراجع. |

**Returns:**
صحيح إذا تم العثور على itemitem في System.Collections.Generic.List؛ وإلا، خطأ.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

ينسخ كامل System.Collections.Generic.List إلى مصفوفة أحادية البعد متوافقة، بدءاً من الفهرس المحدد للمصفوفة الهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| array |  | System.Array أحادي البُعد الذي يكون وجهة العناصر المنقولة من System.Collections.Generic.List. يجب أن يكون لـ System.Array فهرسة صفرية. |
| arrayIndex |  | الفهرس الصفري في array الذي يبدأ عنده النسخ. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

يحصل أو يعيّن الفقرة من أو إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الفقرة. |

**Returns:**
العنصر عند الفهرس المحدد.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأول داخل System.Collections.Generic.List بأكمله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item |  | الكائن الذي يُحدد موقعه في System.Collections.Generic.List. يمكن أن تكون القيمة null لأنواع المراجع. |

**Returns:**
الفهرس الصفري لأول ظهور لـ itemitem داخل System.Collections.Generic.List بأكمله، إذا وُجد؛ وإلا، –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

يدرج عنصراً في System.Collections.Generic.List عند الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس الصفري الذي يجب إدراج item فيه. |
| item |  | الكائن المراد إدراجه. يمكن أن تكون القيمة null لأنواع المراجع. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على القيمة التي تشير إلى ما إذا كانت المجموعة للقراءة فقط.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

يعيد عداداً يتنقل عبر System.Collections.Generic.List.

**Returns:**
مُعدِّد لـ System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد في System.Collections.Generic.List.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس الصفري للعنصر المراد إزالته. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

يزيل أول ظهور لكائن محدد من System.Collections.Generic.List.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item |  | الكائن المراد إزالته من System.Collections.Generic.List. يمكن أن تكون القيمة null لأنواع المراجع. |

**Returns:**
true إذا تم إزالة itemitem بنجاح؛ وإلا، false. تُعيد هذه الطريقة أيضًا false إذا لم يتم العثور على itemitem في System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

يحصل أو يعيّن الفقرة من أو إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الفقرة. |

### size {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة في System.Collections.Generic.List.

**Returns:**
عدد العناصر الموجودة في System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

يقوم بتحديث معامل boundsCheckMode للمجموعة المُهيأة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| boundsCheckMode |  | وضع فحص الحدود. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

يقوم بتحديث معامل boundsCheckMode للمجموعة المُهيأة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| boundsCheckMode |  | وضع فحص الحدود. |
| containerWidth |  | عرض الحاوية. |
| containerHeight |  | ارتفاع الحاوية. |
