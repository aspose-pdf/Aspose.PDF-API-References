---
title: "الفئة LlamaChatCompletionResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.LlamaChatCompletionResponse. تمثّل استجابة إكمال الدردشة التي يُرجعها النموذج بناءً على الإدخال المقدم"
type: docs
weight: 740
url: /ar/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse class

يمثل استجابة إكمال محادثة تُرجعها النموذج، بناءً على الإدخال المقدم.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | يحصل أو يضبط قائمة بخيارات إكمال الدردشة. يمكن أن تكون أكثر من واحدة إذا كان n أكبر من 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | يحصل أو يضبط الطابع الزمني Unix (بالثواني) للوقت الذي تم فيه إنشاء إكمال الدردشة. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | يحصل أو يضبط معرّفًا فريدًا لإكمال الدردشة. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم لإكمال الدردشة. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | يحصل أو يضبط نوع الكائن، والذي يكون دائمًا chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | يحصل أو يضبط بصمة الإصبع التي تمثل تكوين الخلفية الذي يعمل به النموذج. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | يحصل أو يضبط إحصاءات الاستخدام لطلب الإكمال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | يرجع تمثيلًا نصيًا للاختيار الأول. |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


