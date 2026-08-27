---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مصدر ملف خط واحد."
type: docs
weight: 3040
url: /ar/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

يمثل مصدر ملف خط واحد.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | يُهيئ مثيلًا جديدًا من الفئة {@code MemoryFontSource}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [dispose](#dispose--) | يطلق الموارد الداخلية. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [equals](#equals-java.lang.Object-) | تحقق مما إذا كانت كائنات مصدر ملف الخط متساوية. |
| [getFontBytes](#getFontBytes--) | مصفوفة بايت لملف الخط. |
| [hashCode](#hashCode--) | إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

يُهيئ مثيلًا جديدًا من الفئة {@code MemoryFontSource}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontBytes |  | مصفوفة بايت لملف الخط. |

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

يطلق الموارد الداخلية. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### equals {#equals-java.lang.Object-}
تحقق مما إذا كانت كائنات مصدر ملف الخط متساوية.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

مصفوفة بايت لملف الخط.

**Returns:**
مصفوفة byte[]

### hashCode {#hashCode--}
```
public int hashCode()
```

إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
