---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse class. يمثل خطوة في تنفيذ عملية
type: docs
weight: 1060
url: /ar/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

يمثل خطوة في تنفيذ عملية.

```csharp
public class RunStepResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | يحصل أو يحدد معرف المساعد المرتبط بخطوة التشغيل. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إلغاء خطوة التشغيل. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما اكتملت خطوة التشغيل. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء خطوة التشغيل. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل أو يحدد معلومات الخطأ. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما انتهت صلاحية خطوة التشغيل. تعتبر الخطوة منتهية إذا كانت العملية الأصلية منتهية. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما فشلت خطوة التشغيل. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | يحصل أو يحدد معرف خطوة التشغيل، والذي يمكن الإشارة إليه في نقاط نهاية API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | يحصل أو يحدد آخر خطأ مرتبط بهذه الخطوة. سيكون فارغًا إذا لم يكن هناك أخطاء. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | يحصل أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم التي يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، والذي يكون دائمًا thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | يحصل أو يحدد معرف العملية التي تكون هذه الخطوة جزءًا منها. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | يحصل أو يحدد نوع خطوة التشغيل، والتي يمكن أن تكون إما message_creation أو tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | يحصل أو يحدد حالة خطوة التشغيل، والتي يمكن أن تكون إما in_progress أو cancelled أو failed أو completed أو expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | يحصل أو يحدد تفاصيل خطوة التشغيل. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | يحصل أو يحدد معرف الخيط الذي تم تشغيله. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | يحصل أو يحدد إحصائيات الاستخدام المتعلقة بخطوة التشغيل. ستكون هذه القيمة فارغة بينما تكون حالة خطوة التشغيل قيد التقدم. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)