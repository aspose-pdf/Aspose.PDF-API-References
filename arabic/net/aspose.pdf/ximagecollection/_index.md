---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.XImageCollection. فئة تمثل مجموعة XImage
type: docs
weight: 11360
url: /ar/net/aspose.pdf/ximagecollection/
---
## XImageCollection class

فئة تمثل مجموعة XImage.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | عدد الصور في المجموعة. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | يرجع true إذا كان الكائن متزامنًا. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | يحصل على الصورة من المجموعة بواسطة فهرسها. (2 فهرس) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | يحصل على مصفوفة من أسماء الصور. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | يرجع كائن التزامن. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | يضيف كائنًا إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكائن بواسطة الفهرس الأخير. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | يضيف كائنًا إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكائن بواسطة الفهرس الأخير. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | يضيف صورة جديدة إلى قائمة الصور. هذه الطريقة تضيف الصورة كمرجع إلى نفس PdfObject (مما يسمح بتقليل حجم الملف) |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | يضيف كائنًا إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكائن بواسطة الفهرس الأخير. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | يضيف كائنًا إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكائن بواسطة الفهرس الأخير. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | يضيف كائنًا إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكائن بواسطة الفهرس الأخير. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | يمسح جميع العناصر من المجموعة. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | ينسخ مصفوفة من الصور إلى المجموعة. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | يحذف الصور من المجموعة. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | يزيل الفهرس من المجموعة بواسطة الفهرس. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | يزيل العنصر من المجموعة بواسطة الاسم. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | يزيل الصورة من المجموعة بواسطة الفهرس مع تنفيذ الإجراء المحدد بواسطة معلمة الإجراء. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | يزيل العنصر من المجموعة بواسطة الاسم. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | يرجع عداد المجموعة. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | يرجع الاسم في قائمة الصور والذي هو مفتاح الصورة المعطاة. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | يزيل العنصر من المجموعة، ويرمي NotImplementedException. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | يستبدل الصورة في المجموعة بصورة أخرى. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | يستبدل الصورة في المجموعة بصورة أخرى. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | يستبدل الصورة في المجموعة بصورة أخرى. |

### See Also

* class [XImage](../ximage/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)