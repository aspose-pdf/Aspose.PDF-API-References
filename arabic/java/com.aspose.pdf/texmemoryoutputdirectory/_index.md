---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يُنفّذ جلب تدفق إخراج من الذاكرة. يمكنك استخدامه، على سبيل المثال، عندما لا تريد أن يُكتب الإخراج المصاحب (مثل ملف السجل) إلى القرص ولكنك ترغب في ذلك."
type: docs
weight: 4880
url: /ar/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

ينفّذ جلب تدفق إخراج من الذاكرة. يمكنك استخدامه، على سبيل المثال، عندما لا ترغب في كتابة الإخراج المرافق (مثل ملف سجل) إلى القرص ولكنك تريد قراءته لاحقًا من الذاكرة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | ينشئ نسخة جديدة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | يُفرغ الكائن. @throws IOException قد يُرمى استثناء IOException إذا حدث خطأ في الإدخال/الإخراج. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | يعيد التدفق للقراءة منه. دون البحث عن ملف في الأدلة الفرعية. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | يعيد التدفق للقراءة منه. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | يعيد التدفق للكتابة إليه. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

ينشئ نسخة جديدة.

### close {#close--}
```
public void close() throws IOException
```

يُفرغ الكائن. @throws IOException قد يُرمى استثناء IOException إذا حدث خطأ في الإدخال/الإخراج.

### getFile {#getFile-java.lang.String-java.lang.String:A-}
يعيد التدفق للقراءة منه. دون البحث عن ملف في الأدلة الفرعية.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
يعيد التدفق للقراءة منه.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
يعيد التدفق للكتابة إليه.
