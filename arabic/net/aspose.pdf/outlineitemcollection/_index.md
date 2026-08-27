---
title: "الفئة OutlineItemCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.OutlineItemCollection. تمثل إدخال المخطط في تسلسل المخطط الهرمي لمستند PDF"
type: docs
weight: 8150
url: /ar/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

يمثل مدخل المخطط في تسلسل هيكل المخطط لمستند PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | يُهيئ نسخة عنصر المخطط باستخدام كائن التسلسل الجذري. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | يحصل أو يعيّن الإجراء لهذا العنصر في المخطط. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | يحصل أو يعيّن علامة الخط العريض لنص العنوان لهذا العنصر في المخطط |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | يحصل أو يعيّن اللون لنص العنوان لهذا العنصر في المخطط. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | عدد عناصر المجموعة. يرجى عدم الخلط مع VisibleCount: يحصل VisibleCount على عدد عناصر المخطط المرئية على جميع المستويات. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | يحصل أو يعيّن الوجهة لهذا العنصر في المخطط. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | يحصل على عنصر المخطط الذي يمثل أول عنصر من المستوى الأعلى في تسلسل المخطط. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | تحقق مما إذا كان عنصر المخطط يمثل العنصر التالي بالنسبة لهذا العنصر في تسلسل المخطط. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | يحصل على القيمة التي تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخطوط). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | يحصل أو يعيّن علامة المائل لنص العنوان لهذا العنصر في المخطط |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | يحصل على عنصر المخطط من المجموعة باستخدام الفهرس. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | يحصل على عنصر المخطط الذي يمثل آخر عنصر من المستوى الأعلى في تسلسل المخطط. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | يحصل على مستوى التسلسل الهرمي لعنصر المخطط. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | يحصل على عنصر المخطط الذي يمثل العنصر التالي بالنسبة لهذا العنصر في تسلسل المخطط. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | الحصول أو تعيين حالة الفتح (true/false) لعنصر المخطط. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | يحصل على كائن الأصل لهذا العنصر في تسلسل المخطط. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | يحصل على عنصر المخطط الذي يمثل العنصر السابق بالنسبة لهذا العنصر في تسلسل المخطط. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | يحصل على الكائن الذي يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | يحصل أو يعين العنوان لهذا العنصر في المخطط. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | يحصل على العدد الإجمالي لعناصر المخطط على جميع المستويات في تسلسل مخطط المستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | يضيف عنصر المخطط إلى المجموعة. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | يمسح جميع العناصر من المجموعة. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | يتحقق مما إذا كانت المجموعة تحتوي على العنصر المحدد. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | ينسخ إدخالات المخطط إلى System.Array، بدءًا من فهرس System.Array معين. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | يحذف هذا العنصر من تسلسل مخطط المستند. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | يحذف إدخال المخطط بالاسم المحدد من تسلسل مخطط المستند. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | يدرج عنصر المخطط في المجموعة في المكان المحدد. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | إزالة العنصر حسب الفهرس. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | إزالة عنصر مجموعة المخطط. |

### انظر أيضًا

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


