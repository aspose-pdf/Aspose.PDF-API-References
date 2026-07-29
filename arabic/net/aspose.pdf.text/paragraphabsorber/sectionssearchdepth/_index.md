---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية ParagraphAbsorber. تحصّل أو تعيين القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة عن عناصر بنية أدق. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث عن الأقسام، العناوين، الفقرات، إلخ المقسمة أفقياً، وثلاث عمليات بحث عن العناصر المقسمة رأسياً مثل الأعمدة."
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

يحصل أو يعيّن القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقياً (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عمودياً (الأعمدة).

```csharp
public int SectionsSearchDepth { get; set; }
```

## ملاحظات

قد يؤدي زيادة هذه القيمة إلى انخفاض طفيف في الأداء دون أي تغييرات مرئية في نتائج البحث. قد يؤدي تقليل هذه القيمة إلى تحديد غير صحيح للفقرات داخل الأقسام. لا نوصي بتعيين قيمة أقل من الافتراضية إذا لم تكن ترغب في الحصول فقط على العناصر 'الخامة' لبنية الصفحة.

### انظر أيضًا

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


