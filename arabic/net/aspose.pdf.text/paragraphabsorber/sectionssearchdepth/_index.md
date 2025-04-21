---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: خاصية ParagraphAbsorber. تحصل أو تعين قيمة تحدد عدد المرات التي سيتم فيها إجراء عمليات بحث متسلسلة عن عناصر هيكلية أكثر دقة. عمق البحث الافتراضي هو 3. وهذا يعني ثلاث عمليات بحث عن الأقسام المقسمة أفقياً  وثلاث عمليات بحث عن الأقسام المقسمة عمودياً .
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## خاصية ParagraphAbsorber.SectionsSearchDepth

تحصل أو تعين قيمة تحدد عدد المرات التي سيتم فيها إجراء عمليات بحث متسلسلة عن عناصر هيكلية أكثر دقة. عمق البحث الافتراضي هو 3. وهذا يعني ثلاث عمليات بحث عن الأقسام المقسمة أفقياً (العناوين، الفقرات، إلخ) وثلاث عمليات بحث عن الأقسام المقسمة عمودياً (الأعمدة).

```csharp
public int SectionsSearchDepth { get; set; }
```

## ملاحظات

زيادة هذه القيمة قد تؤدي إلى انخفاض طفيف في الأداء دون تغييرات مرئية في نتائج البحث. تقليل هذه القيمة قد يؤدي إلى تحديد غير صحيح للفقرات في الأقسام. لا نوصي بتعيين قيمة أقل من الافتراضي إذا لم تكن ترغب في الحصول على عناصر "خشنة" فقط من هيكل الصفحة.

### انظر أيضًا

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)