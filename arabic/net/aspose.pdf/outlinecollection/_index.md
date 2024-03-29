---
title: OutlineCollection
second_title: Aspose.PDF لمرجع .NET API
description: يمثل التسلسل الهرمي لمخطط المستند.
type: docs
weight: 5760
url: /ar/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

يمثل التسلسل الهرمي لمخطط المستند.

```csharp
public sealed class OutlineCollection : Outlines
```

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count) { get; } | عدد عناصر المجموعة. الرجاء عدم الخلط بينه وبين VisibleCount: يحصل VisibleCount على عدد عناصر المخطط التفصيلي المرئي على جميع المستويات. |
| [First](../../aspose.pdf/outlinecollection/first) { get; } | الحصول على عنصر مخطط يمثل أول عنصر ذي مستوى أعلى في المخطط التفصيلي. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (مؤشر ترابط آمن). |
| [Item](../../aspose.pdf/outlinecollection/item) { get; } | الحصول على عنصر مخطط من المجموعة حسب الفهرس . |
| [Last](../../aspose.pdf/outlinecollection/last) { get; } | الحصول على عنصر مخطط يمثل آخر عنصر مستوى أعلى في المخطط التفصيلي. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot) { get; } | الحصول على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount) { get; } | Count هو مجموع عدد عناصر المخطط التفصيلي التنازلي المرئية على جميع المستويات. ملاحظة: من فضلك لا تخلط مع Count وهو رقم إذا كانت العناصر في المجموعة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add)(OutlineItemCollection) | إضافة عنصر مخطط إلى المجموعة. |
| override [Clear](../../aspose.pdf/outlinecollection/clear)() | مسح كافة العناصر من المجموعة. |
| override [Contains](../../aspose.pdf/outlinecollection/contains)(OutlineItemCollection) | الشيكات لا تحتوي على عنصر معين. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto)(OutlineItemCollection[], int) | نسخ عناصر المخطط التفصيلي إلى System.Array ، بدءًا من فهرس System.Array معين. |
| [Delete](../../aspose.pdf/outlinecollection/delete#delete)() | حذف كافة عناصر المخطط التفصيلي من مخطط المستند. |
| [Delete](../../aspose.pdf/outlinecollection/delete#delete_1)(string) | حذف عنصر المخطط التفصيلي بالعنوان المحدد من مخطط المستند. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [Remove](../../aspose.pdf/outlinecollection/remove#remove_1)(int) | إزالة العنصر بالفهرس . |
| override [Remove](../../aspose.pdf/outlinecollection/remove#remove)(OutlineItemCollection) | رميات دائماNotImplementedException |

### أنظر أيضا

* class [Outlines](../outlines)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
