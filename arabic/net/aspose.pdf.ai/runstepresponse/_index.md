---
title: "الفئة RunStepResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.RunStepResponse. تمثّل خطوة في تنفيذ تشغيل."
type: docs
weight: 1140
url: /ar/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

يمثل خطوة في تنفيذ التنفيذ.

```csharp
public class RunStepResponse : BaseResponse
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | يتم الحصول على أو تعيين معرّف المساعد المرتبط بخطوة التشغيل. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | يتم الحصول على أو تعيين الطابع الزمني لنظام يونكس (بالثواني) للوقت الذي أُلغي فيه خطوة التشغيل. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | يتم الحصول على أو تعيين الطابع الزمني لنظام يونكس (بالثواني) للوقت الذي اكتملت فيه خطوة التشغيل. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | يتم الحصول على أو تعيين الطابع الزمني لنظام يونكس (بالثواني) للوقت الذي تم إنشاء خطوة التشغيل فيه. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | يتم الحصول على أو تعيين الطابع الزمني لنظام يونكس (بالثواني) للوقت الذي انتهت فيه صلاحية خطوة التشغيل. تُعتبر الخطوة منتهية الصلاحية إذا انتهت صلاحية التشغيل الأصلي. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | يتم الحصول على أو تعيين الطابع الزمني لنظام يونكس (بالثواني) للوقت الذي فشلت فيه خطوة التشغيل. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | يتم الحصول على أو تعيين معرف خطوة التشغيل، والذي يمكن الإشارة إليه في نقاط نهاية API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | يتم الحصول على أو تعيين الخطأ الأخير المرتبط بهذه خطوة التشغيل. سيكون فارغًا (null) إذا لم توجد أخطاء. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | يتم الحصول على أو تعيين نوع الكائن، والذي يكون دائمًا thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | يحصل أو يعيّن معرف (ID) التشغيل الذي تكون خطوة التشغيل هذه جزءًا منه. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | يحصل أو يعيّن نوع خطوة التشغيل، والذي يمكن أن يكون إما message_creation أو tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | يحصل أو يعيّن حالة خطوة التشغيل، والتي يمكن أن تكون إما in_progress أو cancelled أو failed أو completed أو expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | يحصل أو يعيّن تفاصيل خطوة التشغيل. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | يحصل أو يعيّن معرف (ID) الخيط الذي تم تشغيله. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | يحصل أو يعيّن إحصاءات الاستخدام المتعلقة بخطوة التشغيل. ستكون هذه القيمة فارغة (null) بينما تكون حالة خطوة التشغيل in_progress. |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


