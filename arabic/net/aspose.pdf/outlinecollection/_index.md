---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.OutlineCollection. تمثل تسلسل مستند المخطط
type: docs
weight: 8000
url: /ar/net/aspose.pdf/outlinecollection/
---
## Class OutlineCollection

تمثل تسلسل مستند المخطط.

```csharp
public sealed class OutlineCollection : Outlines
```

## Properties

| Name | Description |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | عدد عناصر المجموعة. يرجى عدم الخلط مع VisibleCount: VisibleCount يحصل على عدد عناصر المخطط المرئية على جميع المستويات. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | يحصل على عنصر مخطط يمثل أول عنصر على مستوى عالٍ في المخطط. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | يحصل على عنصر مخطط من المجموعة حسب الفهرس. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | يحصل على عنصر مخطط يمثل آخر عنصر على مستوى عالٍ في المخطط. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | العدد هو مجموع عدد عناصر المخطط الفرعية المرئية على جميع المستويات. ملاحظة: يرجى عدم الخلط مع Count الذي هو عدد العناصر في المجموعة. |

## Methods

| Name | Description |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | يضيف عنصر مخطط إلى المجموعة. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | يمسح جميع العناصر من المجموعة. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | يتحقق مما إذا كانت المجموعة تحتوي على العنصر المعطى. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | ينسخ عناصر المخطط إلى مصفوفة System.Array، بدءًا من فهرس مصفوفة معين. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | يحذف جميع عناصر المخطط من مخطط المستند. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | يحذف عنصر المخطط بعنوان محدد من مخطط المستند. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | يعيد عدادًا يتكرر عبر المجموعة. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | يزيل العنصر حسب الفهرس. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | دائمًا ما يرمي NotImplementedException |

### See Also

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)