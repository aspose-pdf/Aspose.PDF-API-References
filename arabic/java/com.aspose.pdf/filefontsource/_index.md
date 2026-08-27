---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مصدر ملف خط واحد."
type: docs
weight: 1450
url: /ar/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

يمثل مصدر ملف خط واحد.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | يُنشئ مثيلًا جديدًا من الفئة {@code FileFontSource}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals](#equals-java.lang.Object-) | تحقق مما إذا كانت كائنات مصدر ملف الخط متساوية. |
| [getFilePath](#getFilePath--) | المسار إلى ملف الخط. |
| [hashCode](#hashCode--) | يُعيد قيمة رمز تجزئة (hash code) للكائن. تُدعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح باستمرار، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يبقى هذا العدد ثابتًا من تنفيذ إلى آخر لنفس التطبيق. <li>إذا كان كائنان متساويان وفقًا لطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس <em>مطلوبًا</em> أنه إذا كان كائنان غير متساويين وفقًا لطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة لكائنات غير متساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا بشكل معقول، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة لكائنات متميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة جافا <span style="font-size:70%"><sup>TM</sup></span>.) |
| [setFilePath](#setFilePath-java.lang.String-) | المسار إلى ملف الخط. |

### FileFontSource {#FileFontSource-java.lang.String-}
يُنشئ مثيلًا جديدًا من الفئة {@code FileFontSource}.

### equals {#equals-java.lang.Object-}
تحقق مما إذا كانت كائنات مصدر ملف الخط متساوية.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

المسار إلى ملف الخط.

**Returns:**
قيمة سلسلة

### hashCode {#hashCode--}
```
public int hashCode()
```

يُعيد قيمة رمز تجزئة (hash code) للكائن. تُدعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح باستمرار، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يبقى هذا العدد ثابتًا من تنفيذ إلى آخر لنفس التطبيق. <li>إذا كان كائنان متساويان وفقًا لطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس <em>مطلوبًا</em> أنه إذا كان كائنان غير متساويين وفقًا لطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة لكائنات غير متساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا بشكل معقول، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة لكائنات متميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة جافا <span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
المسار إلى ملف الخط.
