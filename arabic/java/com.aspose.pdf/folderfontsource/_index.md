---
title: "FolderFontSource"
linktitle: "FolderFontSource"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل المجلد الذي يحتوي على ملفات الخطوط."
type: docs
weight: 1640
url: /ar/java/com.aspose.pdf/folderfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FolderFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FolderFontSource

```
public final class FolderFontSource extends FontSource
```

يمثل المجلد الذي يحتوي على ملفات الخطوط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FolderFontSource](#FolderFontSource-java.lang.String-) | تهيئة نسخة جديدة من الفئة {@code FolderFontSource}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals](#equals-java.lang.Object-) | تحقق مما إذا كانت كائنات مصدر الخط في المجلد متساوية. |
| [getFolderPath](#getFolderPath--) | المسار إلى المجلد الذي يحتوي على ملفات الخطوط. |
| [hashCode](#hashCode--) | إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [setFolderPath](#setFolderPath-java.lang.String-) |  |

### FolderFontSource {#FolderFontSource-java.lang.String-}
تهيئة نسخة جديدة من الفئة {@code FolderFontSource}.

### equals {#equals-java.lang.Object-}
تحقق مما إذا كانت كائنات مصدر الخط في المجلد متساوية.

### getFolderPath {#getFolderPath--}
```
public String getFolderPath()
```

المسار إلى المجلد الذي يحتوي على ملفات الخطوط.

**Returns:**
قيمة سلسلة

### hashCode {#hashCode--}
```
public int hashCode()
```

إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFolderPath {#setFolderPath-java.lang.String-}
