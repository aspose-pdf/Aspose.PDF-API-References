---
title: "الفئة RunThreadCreateRequest"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.RunThreadCreateRequest. تمثل طلبًا لإنشاء خيط وتشغيله في طلب واحد."
type: docs
weight: 1150
url: /ar/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest class

يمثل طلبًا لإنشاء خيط وتنفيذه في طلب واحد.

```csharp
public class RunThreadCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | الحصول أو تعيين معرف المساعد لاستخدامه في تنفيذ هذا التنفيذ. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | الحصول أو تعيين التعليمات التي تتجاوز تعليمات المساعد. هذا مفيد لتعديل السلوك على أساس كل تنفيذ. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | الحصول أو تعيين الحد الأقصى لعدد رموز الإكمال التي قد تُستخدم خلال التنفيذ. سيبذل التنفيذ أقصى جهده لاستخدام عدد رموز الإكمال المحدد فقط، عبر عدة أدوار من التنفيذ. إذا تجاوز التنفيذ عدد رموز الإكمال المحدد، سينتهي التنفيذ بالحالة غير مكتمل. راجع incomplete_details لمزيد من المعلومات. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | الحصول أو تعيين الحد الأقصى لعدد رموز المطالبة التي قد تُستخدم خلال التنفيذ. سيبذل التنفيذ أقصى جهده لاستخدام عدد رموز المطالبة المحدد فقط، عبر عدة أدوار من التنفيذ. إذا تجاوز التنفيذ عدد رموز المطالبة المحدد، سينتهي التنفيذ بالحالة غير مكتمل. راجع incomplete_details لمزيد من المعلومات. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | الحصول أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | الحصول أو تعيين معرف النموذج الذي سيُستخدم لتنفيذ هذا التنفيذ. إذا تم توفير قيمة هنا، فستتجاوز النموذج المرتبط بالمساعد. إذا لم يُقدم، سيُستخدم النموذج المرتبط بالمساعد. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | يحصل أو يعيّن التنسيق الذي يجب أن يُخرج النموذج به. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، مما يضمن أن الرسالة التي يولّدها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا إرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد يولد النموذج تدفقًا لا نهائيًا من الفراغات حتى يصل التوليد إلى حد الرموز، مما ينتج طلبًا طويلًا ويبدو \"عالقًا\". كما يجب ملاحظة أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reason=\"length\"، مما يدل على أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | الحصول أو تعيين ما إذا كان سيتم استخدام البث. إذا كان true، يُرجع تدفقًا من الأحداث التي تحدث أثناء التنفيذ كأحداث مُرسلة من الخادم، وينتهي عندما يدخل التنفيذ حالة نهائية برسالة data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة، بين 0 و 2. القيم الأعلى مثل 0.8 تجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 تجعلها أكثر تركيزًا وحتمية. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | الحصول أو تعيين طلب لإنشاء خيط. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | يحصل أو يعيّن أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none يعني أن النموذج لن يستدعي أي أدوات بل سيولد رسالة بدلاً من ذلك. auto هو القيمة الافتراضية ويعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required يعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {\"type\": \"file_search\"} أو {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} يجبر النموذج على استدعاء تلك الأداة. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | الحصول أو تعيين مجموعة من الموارد التي تستخدمها أدوات المساعد. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | الحصول أو تعيين الأدوات التي تتجاوز الأدوات التي يمكن للمساعد استخدامها لهذا التنفيذ. هذا مفيد لتعديل السلوك على أساس كل تنفيذ. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | الحصول أو تعيين قيمة بديلة للعينات باستخدام درجة الحرارة، تُسمى العينة النواة، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات كتلة الاحتمال top_p. لذا 0.1 يعني أن تُؤخذ فقط الرموز التي تشكل أعلى 10٪ من كتلة الاحتمال. نوصي عمومًا بتعديل هذه القيمة أو درجة الحرارة ولكن ليس كليهما. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | الحصول أو تعيين استراتيجية القطع التي تتحكم في كيفية قطع الخيط قبل التنفيذ. استخدم هذا للتحكم في نافذة السياق الأولية للتنفيذ. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


