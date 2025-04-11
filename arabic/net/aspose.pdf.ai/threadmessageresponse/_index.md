---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse class. يمثل رسالة ضمن سلسلة
type: docs
weight: 1160
url: /ar/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

يمثل رسالة ضمن سلسلة.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | يحصل أو يحدد، إذا كان ذلك مناسبًا، معرف المساعد الذي كتب هذه الرسالة. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | يحصل أو يحدد قائمة الملفات المرفقة بالرسالة. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما اكتملت الرسالة. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | يحصل أو يحدد محتوى الرسالة في مصفوفة من النصوص و/أو الصور. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء الرسالة. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل أو يحدد معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | يحصل أو يحدد المعرف، الذي يمكن الإشارة إليه في نقاط نهاية API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم وضع علامة على الرسالة على أنها غير مكتملة. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | يحصل أو يحدد رسالة غير مكتملة، تفاصيل حول سبب عدم اكتمال الرسالة. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | يحصل أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم التي يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، الذي يكون دائمًا "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | يحصل أو يحدد الكيان الذي أنتج الرسالة. واحد من "مستخدم" أو "مساعد". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | يحصل أو يحدد معرف التشغيل المرتبط بإنشاء هذه الرسالة. القيمة تكون null عندما يتم إنشاء الرسائل يدويًا. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | يحصل أو يحدد حالة الرسالة. واحدة من queued , in_progress , requires_action , أو completed . |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | يحصل أو يحدد معرف السلسلة التي تنتمي إليها هذه الرسالة. |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)