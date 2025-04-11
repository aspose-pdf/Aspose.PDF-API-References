---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.LlamaChatCompletionResponse. تمثل استجابة إكمال الدردشة التي تم إرجاعها بواسطة النموذج بناءً على الإدخال المقدم
type: docs
weight: 690
url: /ar/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse class

تمثل استجابة إكمال الدردشة التي تم إرجاعها بواسطة النموذج، بناءً على الإدخال المقدم.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | يحصل أو يحدد قائمة بخيارات إكمال الدردشة. يمكن أن تكون أكثر من واحدة إذا كان n أكبر من 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء إكمال الدردشة. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل أو يحدد معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | يحصل أو يحدد معرفًا فريدًا لإكمال الدردشة. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | يحصل أو يحدد النموذج المستخدم لإكمال الدردشة. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، والذي يكون دائمًا chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | يحصل أو يحدد بصمة تمثل تكوين الخلفية الذي يعمل به النموذج. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | يحصل أو يحدد إحصائيات الاستخدام لطلب الإكمال. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | يُرجع تمثيل سلسلة للخيار الأول. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)