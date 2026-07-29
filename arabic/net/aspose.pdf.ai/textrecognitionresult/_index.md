---
title: "الفئة TextRecognitionResult"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.TextRecognitionResult. تمثل نتائج OCR المجمعة لمستند مصدر واحد"
type: docs
weight: 1180
url: /ar/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

يمثل نتائج OCR المجمعة لمستند مصدر واحد.

```csharp
public class TextRecognitionResult
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | قائمة تحتوي على نتائج OCR التفصيلية لكل صفحة من المستند. بالنسبة للملفات ذات الصورة الواحدة، عادةً ما تحتوي هذه القائمة على إدخال OcrDetail واحد مع PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | يشير إلى ما إذا كان OCR ناجحًا لجميع الصفحات داخل هذا المستند. يكون خاطئًا إذا كان أي OcrDetail في OcrDetails يحتوي على Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | معرّف للملف المصدر (مثلاً المسار الكامل أو اسم فريد). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | رسالة خطأ موحدة إذا كان OverallSuccess خاطئًا، أو ملخص إذا فشلت أي صفحة. تكون Null إذا كان OverallSuccess صحيحًا. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | يحصل أو يعيّن إحصاءات الاستخدام الكلية لمعالجة هذا المستند (جميع الصفحات). |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


