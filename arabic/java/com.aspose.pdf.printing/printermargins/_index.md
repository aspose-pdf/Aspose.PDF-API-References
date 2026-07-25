---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد أبعاد هوامش الصفحة المطبوعة."
type: docs
weight: 70
url: /ar/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

يحدد أبعاد هوامش الصفحة المطبوعة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | يُنشئ مثيلاً جديداً لفئة Margins بهوامش بعرض بوصة واحدة. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | يُنشئ مثيلاً جديداً لفئة Margins بالهوامش اليسرى واليمنى والعليا والسفلى المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | يسترجع نسخة مكررة من هذا الكائن، عضوًا تلو الآخر. |
| [equals](#equals-java.lang.Object-) | يقارن هذا الـ Margins بالـ Object المحدد لتحديد ما إذا كان لهما نفس الأبعاد. (يتجاوز Object.Equals(Object).) |
| [getBottom](#getBottom--) | يحصل أو يضبط الهامش السفلي، بوحدة مئات البوصة. |
| [getLeft](#getLeft--) | يحصل أو يضبط عرض الهامش الأيسر، بوحدة مئات البوصة. |
| [getRight](#getRight--) | يحصل أو يضبط عرض الهامش الأيمن، بوحدة مئات البوصة. |
| [getTop](#getTop--) | يحصل أو يضبط عرض الهامش العلوي، بوحدة مئات البوصة. |
| [hashCode](#hashCode--) | إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | يقارن بين Margins لتحديد ما إذا كان لهما نفس الأبعاد. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | يقارن بين Margins لتحديد ما إذا كان عرضهما غير متساوٍ. |
| [setBottom](#setBottom-int-) | يحصل أو يضبط الهامش السفلي، بوحدة مئات البوصة. |
| [setLeft](#setLeft-int-) | يحصل أو يضبط عرض الهامش الأيسر، بوحدة مئات البوصة. |
| [setRight](#setRight-int-) | يحصل أو يضبط عرض الهامش الأيمن، بوحدة مئات البوصة. |
| [setTop](#setTop-int-) | يحصل أو يضبط عرض الهامش العلوي، بوحدة مئات البوصة. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

يُنشئ مثيلاً جديداً لفئة Margins بهوامش بعرض بوصة واحدة.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

يُنشئ مثيلاً جديداً لفئة Margins بالهوامش اليسرى واليمنى والعليا والسفلى المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اليسار |  | قيمة int |
| يمين |  | قيمة int |
| أعلى |  | قيمة int |
| الأسفل |  | قيمة int |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

يسترجع نسخة مكررة من هذا الكائن، عضوًا تلو الآخر.

**Returns:**
كائن PrinterMargins

### equals {#equals-java.lang.Object-}
يقارن هذا الـ Margins بالـ Object المحدد لتحديد ما إذا كان لهما نفس الأبعاد. (يتجاوز Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

يحصل أو يضبط الهامش السفلي، بوحدة مئات البوصة.

**Returns:**
قيمة int

### getLeft {#getLeft--}
```
public int getLeft()
```

يحصل أو يضبط عرض الهامش الأيسر، بوحدة مئات البوصة.

**Returns:**
قيمة int

### getRight {#getRight--}
```
public int getRight()
```

يحصل أو يضبط عرض الهامش الأيمن، بوحدة مئات البوصة.

**Returns:**
قيمة int

### getTop {#getTop--}
```
public int getTop()
```

يحصل أو يضبط عرض الهامش العلوي، بوحدة مئات البوصة.

**Returns:**
قيمة int

### hashCode {#hashCode--}
```
public int hashCode()
```

إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
يقارن بين Margins لتحديد ما إذا كان لهما نفس الأبعاد.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
يقارن بين Margins لتحديد ما إذا كان عرضهما غير متساوٍ.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

يحصل أو يضبط الهامش السفلي، بوحدة مئات البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

يحصل أو يضبط عرض الهامش الأيسر، بوحدة مئات البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

يحصل أو يضبط عرض الهامش الأيمن، بوحدة مئات البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

يحصل أو يضبط عرض الهامش العلوي، بوحدة مئات البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
