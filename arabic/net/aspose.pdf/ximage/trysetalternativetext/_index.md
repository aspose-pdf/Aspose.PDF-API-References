---
title: "XImage.TrySetAlternativeText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة XImage. تحدد النص البديل لصورة XImage على الصفحة"
type: docs
weight: 180
url: /ar/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

يضبط النص البديل لـ XImage على الصفحة.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| alternativeText | String | النص البديل الذي يجب تحديده. |
| صفحة | صفحة | الصفحة التي توجد فيها XImage. |

### قيمة الإرجاع

صحيح إذا تم تعيين alternativeText لـ XImage. خطأ إذا لم يتم تعيين alternativeText لـ XImage.

## ملاحظات

تعيد الطريقة قيمة خطأ في الحالات التالية: - لا يتم العثور على XImage في الصفحة المحددة. - تظهر XImage عدة مرات في الصفحة مع عناصر هيكلية مختلفة، مما يجعل من غير الواضح أي نسخة يجب أن تتلقى النص البديل.

### انظر أيضًا

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


