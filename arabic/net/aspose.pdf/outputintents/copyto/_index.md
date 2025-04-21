---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: طريقة OutputIntents. تنسخ عناصر المجموعة إلى المصفوفة بدءًا من arrayIndex المحدد في المصفوفة
type: docs
weight: 70
url: /ar/net/aspose.pdf/outputintents/copyto/
---
## طريقة OutputIntents.CopyTo

تنسخ عناصر المجموعة إلى *array*، بدءًا من *arrayIndex* المحدد في المصفوفة.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | OutputIntent[] | المصفوفة أحادية البعد التي هي وجهة نوايا الإخراج المنسوخة من المجموعة. يجب أن تحتوي المصفوفة على فهرسة تبدأ من الصفر. |
| arrayIndex | Int32 | الفهرس الذي يبدأ من الصفر في *array* والذي يبدأ عنده النسخ. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | *array* فارغ. |
| ArgumentOutOfRangeException | *arrayIndex* أقل من 0. |
| ArgumentException | عدد العناصر في المصدر [`OutputIntents`](../) أكبر من المساحة المتاحة من *arrayIndex* إلى نهاية *array* الوجهة. |

### انظر أيضًا

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)