---
title: "Position"
linktitle: "Position"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل كائن موقع."
type: docs
weight: 3940
url: /ar/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

يمثل كائن موقع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Position](#Position-double-double-) | يُنشئ مثيلًا جديدًا للفئة {@code Position} |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي كائن {@code Position} الحالي. |
| [getXIndent](#getXIndent--) | يحصل على إحداثي X للكائن |
| [getYIndent](#getYIndent--) | يحصل على إحداثي Y للكائن |
| [hashCode](#hashCode--) | إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [setXIndent](#setXIndent-double-) | يضبط إحداثي X للكائن |
| [setYIndent](#setYIndent-double-) | يضبط إحداثي Y للكائن |
| [toString](#toString--) | يحصل على تمثيل النص للكائن {@code Position} الحالي. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

يُنشئ مثيلًا جديدًا للفئة {@code Position}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| xIndent |  | قيمة إحداثي X. |
| yIndent |  | قيمة إحداثي Y. |

### equals {#equals-java.lang.Object-}
يحدد ما إذا كان الكائن المحدد يساوي كائن {@code Position} الحالي.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

يحصل على إحداثي X للكائن

**Returns:**
قيمة double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

يحصل على إحداثي Y للكائن

**Returns:**
قيمة double

### hashCode {#hashCode--}
```
public int hashCode()
```

إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

يضبط إحداثي X للكائن

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

يضبط إحداثي Y للكائن

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toString {#toString--}
```
public String toString()
```

يحصل على تمثيل النص للكائن {@code Position} الحالي.

**Returns:**
تمثيل النص لكائن Position.
