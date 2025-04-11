---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: خاصية OutputIntents. يحصل على نية الإخراج في الفهرس المحدد
type: docs
weight: 30
url: /ar/net/aspose.pdf/outputintents/item/
---
## فهرس OutputIntents

يحصل على نية الإخراج في *الفهرس* المحدد.

```csharp
public OutputIntent this[int index] { get; }
```

| المعامل | الوصف |
| --- | --- |
| index | الفهرس المعتمد على الصفر لنية الإخراج المراد الحصول عليها. |

### قيمة الإرجاع

نية الإخراج في *الفهرس* المحدد.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentOutOfRangeException | *الفهرس* أقل من 0 أو *الفهرس* يساوي أو أكبر من [`Count`](../count/). |
| InvalidOperationException | المستند الذي يحتوي على المجموعة ليس لديه فهرس للوصول إلى OutputIntents. |

### انظر أيضًا

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)