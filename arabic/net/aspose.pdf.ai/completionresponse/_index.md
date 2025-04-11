---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.CompletionResponse. تمثل استجابة إكمال الدردشة التي تم إرجاعها بواسطة النموذج بناءً على الإدخال المقدم
type: docs
weight: 240
url: /ar/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

تمثل استجابة إكمال الدردشة التي تم إرجاعها بواسطة النموذج، بناءً على الإدخال المقدم.

```csharp
public class CompletionResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [CompletionResponse](completionresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | يحصل أو يحدد قائمة بخيارات إكمال الدردشة. يمكن أن يكون هناك أكثر من خيار واحد إذا كان n أكبر من 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء إكمال الدردشة. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل أو يحدد معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | يحصل أو يحدد معرف فريد لإكمال الدردشة. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | يحصل أو يحدد النموذج المستخدم لإكمال الدردشة. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، والذي يكون دائمًا chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | يحصل أو يحدد بصمة تمثل تكوين الخلفية الذي يعمل به النموذج. يمكن استخدامها مع معلمة طلب البذور لفهم متى تم إجراء تغييرات في الخلفية قد تؤثر على الحتمية. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | يحصل أو يحدد إحصائيات الاستخدام لطلب الإكمال. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | يُرجع محتوى الخيار الأول كسلسلة. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)