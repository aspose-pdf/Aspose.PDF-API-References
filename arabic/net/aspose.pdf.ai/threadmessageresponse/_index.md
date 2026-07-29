---
title: "الفئة ThreadMessageResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.AI.ThreadMessageResponse class. يمثل رسالة داخل سلسلة."
type: docs
weight: 1250
url: /ar/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

يمثل رسالة داخل سلسلة.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | يحصل أو يعيّن، إذا كان ذلك مناسبًا، معرّف المساعد الذي أنشأ هذه الرسالة. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | يحصل أو يضبط قائمة بالملفات المرفقة بالرسالة. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | يحصل أو يعيّن الطابع الزمني Unix (بالثواني) للوقت الذي اكتملت فيه الرسالة. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | يحصل أو يعيّن محتوى الرسالة في مصفوفة من النص و/أو الصور. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | يحصل أو يعيّن الطابع الزمني Unix (بالثواني) للوقت الذي تم إنشاء الرسالة فيه. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | يحصل أو يعيّن المعرف، الذي يمكن الإشارة إليه في نقاط النهاية API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | يحصل أو يعيّن الطابع الزمني Unix (بالثواني) للوقت الذي تم فيه وضع علامة على الرسالة كغير مكتملة. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | يحصل أو يعيّن رسالة غير مكتملة، تفاصيل حول سبب عدم اكتمال الرسالة. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | يحصل أو يعيّن نوع الكائن، والذي يكون دائمًا \"thread.message\". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | يحصل أو يعيّن الكيان الذي أنشأ الرسالة. أحد \"user\" أو \"assistant\". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | يحصل أو يعيّن معرّف التشغيل المرتبط بإنشاء هذه الرسالة. تكون القيمة فارغة عندما تُنشأ الرسائل يدويًا. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | يحصل أو يعيّن حالة الرسالة. أحد queued ، in_progress ، requires_action ، أو completed . |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | يحصل أو يعيّن الـ ID الخاص بالسلسلة التي تنتمي إليها هذه الرسالة. |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


