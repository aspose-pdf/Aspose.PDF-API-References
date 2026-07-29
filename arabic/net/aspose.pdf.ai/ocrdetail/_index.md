---
title: "الفئة OcrDetail"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.OcrDetail. تمثل نتيجة OCR لصفحة واحدة من مستند أو ملف صورة واحد"
type: docs
weight: 860
url: /ar/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

يمثل نتيجة OCR لصفحة واحدة من مستند أو ملف صورة واحد.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OcrDetail](ocrdetail/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | رسالة خطأ تصف سبب فشل OCR لهذه الصفحة، إذا كان Success هو false. null خلاف ذلك. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | محتوى النص المستخرج من الصفحة. null إذا كان Success هو false أو لم يتم العثور على نص. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | رقم الصفحة داخل المستند المصدر بدءًا من 1. بالنسبة للصور ذات الصفحة الواحدة، سيكون دائمًا 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | يشير إلى ما إذا كان استخراج OCR لهذه الصفحة المحددة ناجحًا. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | يحصل أو يعيّن إحصاءات الاستخدام. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | يقارن نسخة OcrDetail الحالية مع كائن OcrDetail آخر بناءً على خاصية PageNumber الخاصة بهما. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


