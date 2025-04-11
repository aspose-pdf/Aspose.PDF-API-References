---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunResponse class. يمثل تنفيذًا على خيط
type: docs
weight: 1020
url: /ar/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

يمثل تنفيذًا على خيط.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [RunResponse](runresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | يحصل على أو يحدد معرف المساعد المستخدم لتنفيذ هذا التشغيل. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إلغاء التشغيل. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما اكتمل التشغيل. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء التشغيل. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل على أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل على أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل على أو يحدد معلومات الخطأ. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما سينتهي التشغيل. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما فشل التشغيل. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل على أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل على أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | يحصل على أو يحدد المعرف، الذي يمكن الإشارة إليه في نقاط نهاية API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | يحصل على أو يحدد التفاصيل حول سبب عدم اكتمال التشغيل. سيكون null إذا لم يكن التشغيل غير مكتمل. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | يحصل على أو يحدد التعليمات التي استخدمها المساعد لهذا التشغيل. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | يحصل على أو يحدد آخر خطأ مرتبط بهذا التشغيل. سيكون null إذا لم يكن هناك أخطاء. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | يحصل على أو يحدد الحد الأقصى لعدد رموز الاكتمال المحددة التي يُفترض استخدامها خلال فترة التشغيل. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | يحصل على أو يحدد الحد الأقصى لعدد رموز المطالبة المحددة التي يُفترض استخدامها خلال فترة التشغيل. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | يحصل على أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم التي يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | يحصل على أو يحدد النموذج الذي استخدمه المساعد لهذا التشغيل. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | يحصل على أو يحدد نوع الكائن، الذي يكون دائمًا thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | يحصل على أو يحدد التفاصيل حول الإجراء المطلوب لمتابعة التشغيل. سيكون null إذا لم يكن هناك إجراء مطلوب. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | يحصل على أو يحدد التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. تعيين إلى { "type": "json_object" } يمكّن وضع JSON، الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا توجيه النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا لا ينتهي من المسافات البيضاء حتى يصل التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كان finish_reason="length"، مما يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما بدأ التشغيل. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | يحصل على أو يحدد حالة التشغيل، والتي يمكن أن تكون إما في قائمة الانتظار، قيد التقدم، تتطلب إجراءً، إلغاء، ملغاة، فاشلة، مكتملة، غير مكتملة، أو منتهية. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | يحصل على أو يحدد درجة حرارة العينة المستخدمة لهذا التشغيل. إذا لم يتم تعيينها، فإنها تعود إلى 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | يحصل على أو يحدد معرف الخيط الذي تم تنفيذه كجزء من هذا التشغيل. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | يحصل على أو يحدد أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none تعني أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك ينتج رسالة. auto هو القيمة الافتراضية ويعني أن النموذج يمكنه الاختيار بين إنتاج رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {"type": "file_search"} أو {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | يحصل على أو يحدد قائمة الأدوات التي استخدمها المساعد لهذا التشغيل. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | يحصل على أو يحدد قيمة عينة النواة المستخدمة لهذا التشغيل. إذا لم يتم تعيينها، فإنها تعود إلى 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | يحصل على أو يحدد استراتيجية القطع التي تتحكم في كيفية قطع الخيط قبل التشغيل. استخدم هذا للتحكم في نافذة السياق الأولية للتشغيل. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | يحصل على أو يحدد إحصائيات الاستخدام المتعلقة بالتشغيل. ستكون هذه القيمة null إذا لم يكن التشغيل في حالة نهائية (أي قيد التقدم، في قائمة الانتظار، إلخ). |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)