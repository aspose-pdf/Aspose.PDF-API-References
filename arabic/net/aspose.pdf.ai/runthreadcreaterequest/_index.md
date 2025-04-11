---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.RunThreadCreateRequest. تمثل طلبًا لإنشاء خيط وتشغيله في طلب واحد
type: docs
weight: 1070
url: /ar/net/aspose.pdf.ai/runthreadcreaterequest/
---
## فئة RunThreadCreateRequest

تمثل طلبًا لإنشاء خيط وتشغيله في طلب واحد.

```csharp
public class RunThreadCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | يحصل أو يحدد معرف المساعد الذي سيتم استخدامه لتنفيذ هذا التشغيل. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | يحصل أو يحدد التعليمات التي تتجاوز تعليمات المساعد. هذا مفيد لتعديل السلوك على أساس كل تشغيل. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الإكمال التي يمكن استخدامها خلال فترة التشغيل. سيبذل التشغيل جهدًا كبيرًا لاستخدام العدد المحدد فقط من رموز الإكمال، عبر عدة دورات من التشغيل. إذا تجاوز التشغيل عدد رموز الإكمال المحددة، سينتهي التشغيل بحالة غير مكتملة. انظر incomplete_details لمزيد من المعلومات. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الطلب التي يمكن استخدامها خلال فترة التشغيل. سيبذل التشغيل جهدًا كبيرًا لاستخدام العدد المحدد فقط من رموز الطلب، عبر عدة دورات من التشغيل. إذا تجاوز التشغيل عدد رموز الطلب المحددة، سينتهي التشغيل بحالة غير مكتملة. انظر incomplete_details لمزيد من المعلومات. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | يحصل أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | يحصل أو يحدد معرف النموذج الذي سيتم استخدامه لتنفيذ هذا التشغيل. إذا تم توفير قيمة هنا، ستتجاوز النموذج المرتبط بالمساعد. إذا لم يكن كذلك، سيتم استخدام النموذج المرتبط بالمساعد. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | يحصل أو يحدد التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o وGPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. تعيين إلى { "type": "json_object" } يمكّن وضع JSON، الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا توجيه النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا لا نهاية له من المسافات البيضاء حتى يصل التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كان finish_reason="length"، مما يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | يحصل أو يحدد ما إذا كان سيتم استخدام البث. إذا كان صحيحًا، يرجع تدفقًا من الأحداث التي تحدث خلال التشغيل كأحداث مرسلة من الخادم، وتنتهي عندما يدخل التشغيل حالة نهائية مع رسالة data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة التي يجب استخدامها، بين 0 و2. القيم الأعلى مثل 0.8 ستجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 ستجعلها أكثر تركيزًا وحتمية. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | يحصل أو يحدد طلبًا لإنشاء خيط. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | يحصل أو يحدد أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none تعني أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك ينتج رسالة. auto هي القيمة الافتراضية وتعني أن النموذج يمكنه الاختيار بين إنتاج رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {"type": "file_search"} أو {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | يحصل أو يحدد مجموعة من الموارد التي تستخدمها أدوات المساعد. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | يحصل أو يحدد الأدوات التي تتجاوز الأدوات التي يمكن أن يستخدمها المساعد لهذا التشغيل. هذا مفيد لتعديل السلوك على أساس كل تشغيل. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | يحصل أو يحدد قيمة بديلة لعملية العينة باستخدام درجة الحرارة، تسمى عينة النواة، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات الكتلة الاحتمالية top_p. لذا 0.1 تعني أن الرموز التي تتكون من أعلى 10% من الكتلة الاحتمالية فقط هي التي تؤخذ في الاعتبار. نوصي عمومًا بتغيير هذا أو درجة الحرارة ولكن ليس كليهما. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | يحصل أو يحدد استراتيجية الاقتطاع التي تتحكم في كيفية اقتطاع الخيط قبل التشغيل. استخدم هذا للتحكم في نافذة السياق الأولية للتشغيل. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* التجميع [Aspose.PDF](../../)