---
title: "الفئة CompletionCreateRequest"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.CompletionCreateRequest. تمثل طلبًا لنقطة النهاية Create Chat Completion"
type: docs
weight: 230
url: /ar/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

يمثل طلبًا لنقطة النهاية Create Chat Completion.

```csharp
public class CompletionCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | يحصل أو يضبط رقمًا بين -2.0 و 2.0. القيم الإيجابية تعاقب الرموز الجديدة بناءً على تكرارها الحالي في النص حتى الآن، مما يقلل احتمال تكرار النموذج لنفس السطر حرفيًا. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | يحصل أو يضبط احتمال ظهور الرموز المحددة في الإكمال. يقبل كائن JSON يربط الرموز (المحددة بمعرف الرمز في أداة الترميز) بقيمة انحياز من -100 إلى 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | يحصل أو يضبط ما إذا كان يجب إرجاع احتمالات اللوغاريتمية للرموز الناتجة أم لا. إذا كان true، يرجع احتمالات اللوغاريتمية لكل رمز ناتج في محتوى الرسالة. |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد الرموز التي يتم توليدها في الإكمال. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | يحصل أو يضبط قائمة الرسائل التي تشكل المحادثة حتى الآن. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | يحصل أو يضبط معرّف النموذج المراد استخدامه. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | يحصل أو يضبط عدد خيارات إكمال الدردشة التي يتم توليدها لكل رسالة إدخال. لاحظ أنه سيتم احتساب التكلفة بناءً على عدد الرموز المولدة عبر جميع الخيارات. احتفظ بـ n كـ 1 لتقليل التكاليف. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | يحصل أو يضبط رقمًا بين -2.0 و 2.0. القيم الإيجابية تعاقب الرموز الجديدة بناءً على ما إذا كانت تظهر في النص حتى الآن، مما يزيد من احتمال أن يتحدث النموذج عن مواضيع جديدة. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | يحصل أو يضبط كائنًا يحدد التنسيق الذي يجب أن يخرج به النموذج. متوافق مع GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo الأحدث من gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، مما يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | يحصل أو يضبط قيمة البذرة. هذه الميزة في مرحلة التجريب. إذا تم تحديدها، سيحاول نظامنا أخذ عينات بشكل حتمي، بحيث تُعيد الطلبات المتكررة ذات البذرة والمعلمات نفسها النتيجة نفسها. لا يُضمن الحتمية، ويجب الرجوع إلى معلمة الاستجابة system_fingerprint لمراقبة التغييرات في الخلفية. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | يحصل أو يضبط ما يصل إلى 4 سلاسل حيث ستتوقف API عن توليد رموز إضافية. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | يحصل أو يضبط ما إذا كان سيتم استخدام البث. إذا تم الضبط، سيتم إرسال دلتا الرسائل الجزئية، مثلما في ChatGPT. سيتم إرسال الرموز كأحداث خادم-مُرسلة بيانات فقط عندما تصبح متاحة، مع إنهاء البث برسالة data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة، بين 0 و 2. القيم الأعلى مثل 0.8 تجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 تجعلها أكثر تركيزًا وحتمية. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | يحصل أو يضبط كائنًا يتحكم في أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none يعني أن النموذج لن يستدعي أي أداة بل يولد رسالة بدلاً من ذلك. auto يعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required يعني أن النموذج يجب أن يستدعي أداة أو أكثر. تحديد أداة معينة عبر {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} يجبر النموذج على استدعاء تلك الأداة. none هو الإعداد الافتراضي عندما لا توجد أدوات. auto هو الإعداد الافتراضي إذا كانت الأدوات موجودة. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | يحصل أو يضبط قائمة بالأدوات التي قد يستدعيها النموذج. حاليًا، يتم دعم الدوال فقط كأداة. استخدم هذا لتوفير قائمة بالدوال التي قد يولد النموذج مدخلات JSON لها. الحد الأقصى هو 128 دالة مدعومة. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | يحصل أو يضبط بديلاً لدرجة الحرارة يُسمى العينة النواة، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات كتلة الاحتمال top_p. لذا 0.1 يعني أن الرموز التي تشكل أعلى 10% من كتلة الاحتمال فقط تُؤخذ في الاعتبار. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | يحصل أو يضبط معرّفًا فريدًا يمثل المستخدم النهائي الخاص بك، مما يمكن OpenAI من مراقبة واكتشاف الإساءة. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


