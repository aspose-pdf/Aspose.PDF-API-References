---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الإجراء الذي يُنفّذ مع كائن الصورة عندما تُزال الصورة من المجموعة. إذا تم إزالة كائن الصورة"
type: docs
weight: 2290
url: /ar/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

الإجراء الذي يُنفّذ مع كائن الصورة عندما تُزال الصورة من المجموعة. إذا تم إزالة كائن الصورة

## الحقول

| حقل | الوصف |
| --- | --- |
| [Check](#Check) | سيتم إزالة الصورة من المجموعة وسيتم حذف كائن الصورة فقط إذا لم تكن هناك مراجع أخرى للصورة من صفحات أخرى. قد يتطلب هذا وقتًا أطول مقارنةً بخيار ForceDelete. |
| [ForceDelete](#ForceDelete) | سيتم إزالة الصورة من المجموعة وسيتم حذف كائن الصورة من المستند. إذا وجدت مراجع أخرى على نفس الكائن قد يتلف المستند. |
| [KeepContents](#KeepContents) | سيتم إزالة الصورة من المجموعة. إذا احتوى محتوى الصفحة على مراجع للصورة فلن تُزال. قد يصبح المستند غير صالح. |
| [None](#None) | سيتم إزالة الصورة من المجموعة ومن محتوى الصفحة، لكن كائن الصورة لن يُحذف. لن يقل حجم الملف. |

### Check {#Check}
```
public static final int Check
```

سيتم إزالة الصورة من المجموعة وسيتم حذف كائن الصورة فقط إذا لم تكن هناك مراجع أخرى للصورة من صفحات أخرى. قد يتطلب هذا وقتًا أطول مقارنةً بخيار ForceDelete.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

سيتم إزالة الصورة من المجموعة وسيتم حذف كائن الصورة من المستند. إذا وجدت مراجع أخرى على نفس الكائن قد يتلف المستند.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

سيتم إزالة الصورة من المجموعة. إذا احتوى محتوى الصفحة على مراجع للصورة فلن تُزال. قد يصبح المستند غير صالح.

### None {#None}
```
public static final int None
```

سيتم إزالة الصورة من المجموعة ومن محتوى الصفحة، لكن كائن الصورة لن يُحذف. لن يقل حجم الملف.
