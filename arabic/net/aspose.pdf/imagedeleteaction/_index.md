---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction enum. الإجراء الذي يتم تنفيذه مع كائن الصورة عند إزالة الصورة من المجموعة. إذا تم إزالة كائن الصورة
type: docs
weight: 5870
url: /ar/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

الإجراء الذي يتم تنفيذه مع كائن الصورة عند إزالة الصورة من المجموعة. إذا تم إزالة كائن الصورة

```csharp
public enum ImageDeleteAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| KeepContents | `0` | سيتم إزالة الصورة من المجموعة. إذا كانت محتويات الصفحة تحتوي على مراجع للصورة، فلن يتم إزالتها. قد يصبح المستند غير صالح. |
| None | `1` | سيتم إزالة الصورة من المجموعة ومن محتويات الصفحة، ولكن لن يتم حذف كائن الصورة. لن يتم تقليل حجم الملف. |
| ForceDelete | `2` | سيتم إزالة الصورة من المجموعة وسيتم إزالة كائن الصورة من المستند. إذا كانت هناك مراجع أخرى على نفس الكائن، فقد يتعرض المستند للتلف. |
| Check | `3` | سيتم إزالة الصورة من المجموعة وسيتم إزالة كائن الصورة فقط إذا لم تكن هناك مراجع أخرى للصورة من صفحات أخرى. قد يتطلب هذا المزيد من الوقت مقارنةً بخيار ForceDelete. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)