---
title: "IOcrCopilot.GetTextRecognitionResultAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "IOcrCopilot طريقة. تسترجع بشكل غير متزامن نتائج التعرف على النص لمستندات PDF وملفات الصور. أنواع الصور المدعومة PNG .png JPEG .jpeg و .jpg WEBP .webp GIF غير المتحرك .gif."
type: docs
weight: 10
url: /ar/net/aspose.pdf.ai/iocrcopilot/gettextrecognitionresultasync/
---
## IOcrCopilot.GetTextRecognitionResultAsync method

يسترجع بشكل غير متزامن نتائج التعرف على النص لملفات PDF والملفات الصورة. أنواع الصور المدعومة: PNG (.png)، JPEG (.jpeg و .jpg)، WEBP (.webp)، GIF غير المتحرك (.gif).

```csharp
public Task<List<TextRecognitionResult>> GetTextRecognitionResultAsync(
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| cancellationToken | Nullable`1 | رمز إلغاء اختياري لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على قائمة من [`TextRecognitionResult`](../../textrecognitionresult/).

### انظر أيضًا

* class [TextRecognitionResult](../../textrecognitionresult/)
* interface [IOcrCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


