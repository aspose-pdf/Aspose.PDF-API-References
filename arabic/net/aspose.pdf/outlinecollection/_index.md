---
title: "الفئة OutlineCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.OutlineCollection. تمثل التسلسل الهرمي لمخطط المستند"
type: docs
weight: 8140
url: /ar/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

يمثل تسلسل هيكل مخطط المستند.

```csharp
public sealed class OutlineCollection : Outlines
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | عدد عناصر المجموعة. يرجى عدم الخلط مع VisibleCount: يحصل VisibleCount على عدد عناصر المخطط المرئية على جميع المستويات. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | يحصل على عنصر مخطط يمثل العنصر الأول من المستوى الأعلى في المخطط. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | يحصل على عنصر مخطط من المجموعة حسب الفهرس. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | يحصل على عنصر مخطط يمثل العنصر الأخير من المستوى الأعلى في المخطط. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | العدد هو مجموع عدد عناصر المخطط الفرعية المرئية على جميع المستويات. ملاحظة: يرجى عدم الخلط مع Count الذي هو عدد العناصر في المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | يضيف عنصر المخطط إلى المجموعة. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | يمسح جميع العناصر من المجموعة. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | يتحقق مما إذا كانت المجموعة تحتوي على العنصر المحدد. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | ينسخ عناصر المخطط إلى System.Array، بدءًا من فهرس System.Array معين. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | يحذف جميع عناصر المخطط من مخطط المستند. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | يحذف عنصر المخطط الذي له عنوان محدد من مخطط المستند. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | إزالة العنصر حسب الفهرس. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | دائمًا يرمي NotImplementedException |

### انظر أيضًا

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


