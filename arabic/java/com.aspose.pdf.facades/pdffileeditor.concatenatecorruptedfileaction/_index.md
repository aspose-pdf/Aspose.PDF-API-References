---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الإجراء المتخذ عندما يتم مواجهة ملف تالف في عملية الدمج."
type: docs
weight: 420
url: /ar/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

الإجراء المتخذ عندما يتم مواجهة ملف تالف في عملية الدمج.

## الحقول

| حقل | الوصف |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | إذا تم مواجهة ملف تالف، فلا تتوقف عملية الدمج ولا تعالج الملف التالف. قائمة الملفات التالفة يمكن الوصول إليها عبر الخاصية Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | عند مواجهة كائن تالف في المستند المصدر، لن تتوقف العملية وسيتم تجاهل الكائن التالف فقط. |
| [StopWithError](#StopWithError) | إذا تم مواجهة ملف تالف، فقم بإيقاف عملية الدمج وأرجع خطأ. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

إذا تم مواجهة ملف تالف، فلا تتوقف عملية الدمج ولا تعالج الملف التالف. قائمة الملفات التالفة يمكن الوصول إليها عبر الخاصية Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

عند مواجهة كائن تالف في المستند المصدر، لن تتوقف العملية وسيتم تجاهل الكائن التالف فقط.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

إذا تم مواجهة ملف تالف، فقم بإيقاف عملية الدمج وأرجع خطأ.
