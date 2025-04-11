---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Structure.Element. فئة تمثل العنصر الأساسي للبنية المنطقية
type: docs
weight: 10140
url: /ar/net/aspose.pdf.structure/element/
---
## فئة العنصر

فئة تمثل العنصر الأساسي للبنية المنطقية.

```csharp
public abstract class Element
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (اختياري؛ PDF 1.4) نص يمثل بديلاً دقيقًا لعنصر البنية وأطفاله. هذا النص البديل (الذي يجب أن ينطبق على أصغر قطعة ممكنة من المحتوى) مفيد عند استخراج محتويات الوثيقة لدعم الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (اختياري) وصف بديل لعنصر البنية وأطفاله بصيغة قابلة للقراءة البشرية، وهو مفيد عند استخراج محتويات الوثيقة لدعم الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | يحصل على مجموعة العناصر الفرعية. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (اختياري؛ PDF 1.5) الشكل الموسع للاختصار. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (اختياري؛ PDF 1.4) لغة تحدد اللغة الطبيعية لجميع النصوص في عنصر البنية باستثناء حيث يتم تجاوزها بمواصفات اللغة لعناصر البنية المتداخلة أو المحتوى المعلم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | إزالة العنصر. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* التجميع [Aspose.PDF](../../)