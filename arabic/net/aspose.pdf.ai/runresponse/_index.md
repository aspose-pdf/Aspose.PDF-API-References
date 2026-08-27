---
title: "الفئة RunResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.RunResponse. تمثل تشغيل تنفيذ على thread."
type: docs
weight: 1100
url: /ar/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

يمثل تنفيذًا على خيط.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RunResponse](runresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | يحصل أو يعيّن معرّف المساعد المستخدم لتنفيذ هذا التشغيل. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | يحصل أو يعيّن الطابع الزمني يونيكس (بالثواني) للوقت الذي أُلغي فيه التشغيل. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | يحصل أو يعيّن الطابع الزمني يونيكس (بالثواني) للوقت الذي اكتمل فيه التشغيل. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | يحصل أو يعيّن الطابع الزمني يونيكس (بالثواني) للوقت الذي تم فيه إنشاء التشغيل. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | يحصل أو يعيّن الطابع الزمني يونيكس (بالثواني) للوقت الذي سينتهي فيه صلاحية التشغيل. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | يحصل أو يعيّن الطابع الزمني يونيكس (بالثواني) للوقت الذي فشل فيه التشغيل. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | يحصل أو يعيّن المعرف، الذي يمكن الإشارة إليه في نقاط النهاية API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | يحصل أو يعيّن التفاصيل حول سبب عدم اكتمال التشغيل. سيكون فارغًا (null) إذا لم يكن التشغيل غير مكتمل. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | يحصل أو يعيّن التعليمات التي استخدمها المساعد لهذا التشغيل. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | يحصل أو يعيّن الخطأ الأخير المرتبط بهذا التشغيل. سيكون فارغًا (null) إذا لم توجد أخطاء. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد رموز الإكمال المحددة التي تم استخدامها خلال تشغيل العملية. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد رموز المطالبة المحددة التي تم استخدامها خلال تشغيل العملية. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | يحصل أو يعيّن النموذج الذي استخدمه المساعد لهذا التشغيل. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | يحصل أو يعيّن نوع الكائن، والذي يكون دائمًا thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | يحصل أو يعيّن التفاصيل حول الإجراء المطلوب لمتابعة التشغيل. سيكون فارغًا (null) إذا لم يكن هناك أي إجراء مطلوب. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | يحصل أو يعيّن التنسيق الذي يجب أن يُخرج النموذج به. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، مما يضمن أن الرسالة التي يولّدها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا إرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد يولد النموذج تدفقًا لا نهائيًا من الفراغات حتى يصل التوليد إلى حد الرموز، مما ينتج طلبًا طويلًا ويبدو \"عالقًا\". كما يجب ملاحظة أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reason=\"length\"، مما يدل على أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | يحصل أو يعيّن الطابع الزمني يونيكس (بالثواني) للوقت الذي بدأ فيه التشغيل. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | يحصل أو يعيّن حالة التشغيل، والتي يمكن أن تكون إما queued أو in_progress أو requires_action أو cancelling أو cancelled أو failed أو completed أو incomplete أو expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | يحصل أو يعيّن درجة حرارة العينة المستخدمة لهذا التشغيل. إذا لم يتم ضبطها، يكون الافتراضي 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | يحصل أو يعيّن معرّف الخيط الذي تم تنفيذ العملية عليه كجزء من هذا التشغيل. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | يحصل أو يعيّن أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none يعني أن النموذج لن يستدعي أي أدوات بل سيولد رسالة بدلاً من ذلك. auto هو القيمة الافتراضية ويعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required يعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {\"type\": \"file_search\"} أو {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} يجبر النموذج على استدعاء تلك الأداة. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | يحصل أو يعيّن قائمة الأدوات التي استخدمها المساعد لهذا التشغيل. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | يحصل أو يعيّن قيمة العينة النواة المستخدمة لهذا التشغيل. إذا لم يتم ضبطها، يكون الافتراضي 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | الحصول أو تعيين استراتيجية القطع التي تتحكم في كيفية قطع الخيط قبل التنفيذ. استخدم هذا للتحكم في نافذة السياق الأولية للتنفيذ. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | الحصول أو تعيين إحصاءات الاستخدام المتعلقة بالتنفيذ. ستكون هذه القيمة فارغة إذا لم يكن التنفيذ في حالة نهائية (مثل in_progress، queued، إلخ). |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


