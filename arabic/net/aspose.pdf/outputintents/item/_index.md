---
title: "OutputIntents.Item"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية OutputIntents. يحصل على نية الإخراج عند الفهرس المحدد"
type: docs
weight: 30
url: /ar/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

يحصل على نية الإخراج عند *index* المحدد.

```csharp
public OutputIntent this[int index] { get; }
```

| معامل | الوصف |
| --- | --- |
| index | الفهرس الصفري لنية الإخراج التي سيتم الحصول عليها. |

### قيمة الإرجاع

نية الإخراج عند *index* المحدد.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *index* أصغر من 0 أو *index* يساوي أو أكبر من [`Count`](../count/). |
| InvalidOperationException | المستند الذي يحتوي على المجموعة لا يحتوي على فهرس للوصول إلى OutputIntents. |

### انظر أيضًا

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


