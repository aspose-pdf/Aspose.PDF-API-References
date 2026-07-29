---
title: "الفئة TextElement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Structure.TextElement. عنصر نص عام في بنية المستند المنطقية"
type: docs
weight: 10370
url: /ar/net/aspose.pdf.structure/textelement/
---
## TextElement class

عنصر نص عام لهكيل المستند المنطقي.

```csharp
public class TextElement : Element
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (اختياري؛ PDF 1.4) نص يُعد بديلاً دقيقًا لعنصر البنية وأطفاله. هذا النص البديل (الذي يجب أن يُطبق على أصغر جزء من المحتوى ممكن) مفيد عند استخراج محتويات المستند لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (اختياري) وصف بديل لعنصر البنية وأطفاله بصيغة قابلة للقراءة البشرية، وهو مفيد عند استخراج محتويات المستند لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | يحصل على مجموعة العناصر الفرعية. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (اختياري؛ PDF 1.5) الشكل الموسع للاختصار. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (اختياري؛ PDF 1.4) لغة تحدد اللغة الطبيعية لجميع النصوص في عنصر البنية باستثناء الحالات التي يتم فيها تجاوزها بمواصفات اللغة لعناصر البنية المتداخلة أو المحتوى المميز. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | يحصل على قيمة عنصر بنية النص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | إزالة العنصر. |

### انظر أيضًا

* class [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)


