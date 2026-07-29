---
title: "الفئة CompletionResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.CompletionResponse. تمثل استجابة إكمال الدردشة التي يُرجعها النموذج بناءً على الإدخال المقدم"
type: docs
weight: 250
url: /ar/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

يمثل استجابة إكمال محادثة تُرجعها النموذج، بناءً على الإدخال المقدم.

```csharp
public class CompletionResponse : BaseResponse
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CompletionResponse](completionresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | يحصل أو يضبط قائمة بخيارات إكمال الدردشة. يمكن أن تكون أكثر من واحدة إذا كان n أكبر من 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | يحصل أو يضبط الطابع الزمني Unix (بالثواني) للوقت الذي تم فيه إنشاء إكمال الدردشة. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | يحصل أو يضبط معرّفًا فريدًا لإكمال الدردشة. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم لإكمال الدردشة. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | يحصل أو يضبط نوع الكائن، والذي يكون دائمًا chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | يحصل أو يعيّن البصمة التي تمثل تكوين الواجهة الخلفية التي يعمل بها النموذج. يمكن استخدامها بالاشتراك مع معامل طلب البذرة لفهم متى تم إجراء تغييرات على الواجهة الخلفية قد تؤثر على الحتمية. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | يحصل أو يعيّن إحصاءات الاستخدام لطلب الإكمال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | يرجع محتوى الاختيار الأول كسلسلة نصية. |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


