---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.CompletionCreateRequest. تمثل طلبًا لنقطة نهاية إنشاء إكمال الدردشة
type: docs
weight: 220
url: /ar/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

تمثل طلبًا لنقطة نهاية إنشاء إكمال الدردشة.

```csharp
public class CompletionCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | يحصل أو يحدد رقمًا بين -2.0 و 2.0. القيم الإيجابية تعاقب الرموز الجديدة بناءً على تكرارها الحالي في النص حتى الآن، مما يقلل من احتمال تكرار النموذج لنفس السطر حرفيًا. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | يحصل أو يحدد احتمال ظهور رموز معينة في الإكمال. يقبل كائن JSON يربط الرموز (المحددة بواسطة معرف الرمز في المحلل) بقيمة انحياز مرتبطة من -100 إلى 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | يحصل أو يحدد ما إذا كان يجب إرجاع احتمالات السجل للرموز الناتجة أم لا. إذا كانت القيمة صحيحة، يتم إرجاع احتمالات السجل لكل رمز ناتج تم إرجاعه في محتوى الرسالة. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد الرموز التي يجب توليدها في الإكمال. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | يحصل أو يحدد قائمة بالرسائل التي تتكون من المحادثة حتى الآن. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | يحصل أو يحدد معرف النموذج الذي يجب استخدامه. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | يحصل أو يحدد عدد خيارات إكمال الدردشة التي يجب توليدها لكل رسالة إدخال. لاحظ أنك ستتحمل رسومًا بناءً على عدد الرموز المولدة عبر جميع الخيارات. احتفظ بـ n كـ 1 لتقليل التكاليف. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | يحصل أو يحدد رقمًا بين -2.0 و 2.0. القيم الإيجابية تعاقب الرموز الجديدة بناءً على ما إذا كانت تظهر في النص حتى الآن، مما يزيد من احتمال تحدث النموذج عن مواضيع جديدة. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | يحصل أو يحدد كائنًا يحدد التنسيق الذي يجب أن يخرجه النموذج. متوافق مع GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo الأحدث من gpt-3.5-turbo-1106. تعيينه إلى { "type": "json_object" } يمكّن وضع JSON، مما يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | يحصل أو يحدد قيمة البذور. هذه الميزة في النسخة التجريبية. إذا تم تحديدها، سيبذل نظامنا جهدًا أفضل لأخذ عينات بشكل حتمي، بحيث يجب أن تعيد الطلبات المتكررة بنفس البذور والمعلمات نفس النتيجة. لا يتم ضمان الحتمية، ويجب عليك الرجوع إلى معلمة استجابة system_fingerprint لمراقبة التغييرات في الخلفية. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | يحصل أو يحدد ما يصل إلى 4 تسلسلات حيث سيتوقف واجهة برمجة التطبيقات عن توليد رموز إضافية. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | يحصل أو يحدد ما إذا كان يجب استخدام البث. إذا تم تعيينه، سيتم إرسال دلتا الرسالة الجزئية، كما في ChatGPT. سيتم إرسال الرموز كأحداث خادم مرسلة فقط للبيانات عند توفرها، مع إنهاء البث برسالة data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة التي يجب استخدامها، بين 0 و 2. القيم الأعلى مثل 0.8 ستجعل الناتج أكثر عشوائية، بينما القيم الأقل مثل 0.2 ستجعله أكثر تركيزًا وحتمية. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | يحصل أو يحدد كائنًا يتحكم في أي (إن وجد) أداة يتم استدعاؤها بواسطة النموذج. none تعني أن النموذج لن يستدعي أي أداة وبدلاً من ذلك يولد رسالة. auto تعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر. تحديد أداة معينة عبر {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة. none هو الافتراضي عندما لا توجد أدوات. auto هو الافتراضي إذا كانت الأدوات موجودة. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | يحصل أو يحدد قائمة بالأدوات التي قد يستدعيها النموذج. حاليًا، يتم دعم الوظائف فقط كأداة. استخدم هذا لتوفير قائمة بالوظائف التي قد ينتجها النموذج كمدخلات JSON. يتم دعم حد أقصى من 128 وظيفة. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | يحصل أو يحدد بديلاً لأخذ العينات مع درجة الحرارة، يسمى أخذ العينات النووي، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات كتلة احتمال top_p. لذا فإن 0.1 تعني أن الرموز التي تتكون من أعلى 10% من كتلة الاحتمال فقط هي التي تؤخذ في الاعتبار. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | يحصل أو يحدد معرفًا فريدًا يمثل المستخدم النهائي الخاص بك، مما يمكن أن يساعد OpenAI في مراقبة واكتشاف الإساءة. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)