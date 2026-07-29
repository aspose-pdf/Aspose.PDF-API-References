---
title: "OutputIntents.CopyTo"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OutputIntents. ينسخ عناصر المجموعة إلى *array* بدءًا من *arrayIndex* المحدد"
type: docs
weight: 70
url: /ar/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

ينسخ عناصر المجموعة إلى *array*، بدءًا من *arrayIndex* المحدد داخل المصفوفة.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| مصفوفة | OutputIntent[] | المصفوفة أحادية البُعد التي هي وجهة نوايا الإخراج المنسوخة من المجموعة. يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | Int32 | الفهرس الصفري في *array* الذي يبدأ عنده النسخ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *array* فارغ. |
| ArgumentOutOfRangeException | *arrayIndex* أصغر من 0. |
| ArgumentException | عدد العناصر في المصدر [`OutputIntents`](../) أكبر من المساحة المتاحة من *arrayIndex* إلى نهاية *array* الوجهة. |

### انظر أيضًا

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


