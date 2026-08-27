---
title: "الفئة AssistantCreateRequest"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.AssistantCreateRequest. كائن طلب لإنشاء مساعد"
type: docs
weight: 100
url: /ar/net/aspose.pdf.ai/assistantcreaterequest/
---
## AssistantCreateRequest class

كائن الطلب لإنشاء مساعد.

```csharp
public class AssistantCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | يحصل أو يعيّن وصف المساعد. الحد الأقصى للطول هو 512 حرفًا. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | يحصل أو يعيّن تعليمات النظام التي يستخدمها المساعد. الحد الأقصى للطول هو 256,000 حرف. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | يحصل أو يعيّن معرف النموذج لاستخدامه. يمكنك استخدام List models API لرؤية جميع النماذج المتاحة لديك، أو الاطلاع على نظرة عامة على النماذج للحصول على أوصافها. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | يحصل أو يعيّن اسم المساعد. الحد الأقصى للطول هو 256 حرفًا. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | يحصل أو يعيّن التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، والذي يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا إرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد يولد النموذج تدفقًا لا نهائيًا من الفراغات حتى يصل التوليد إلى حد الرموز، مما ينتج طلبًا طويل الأمد ويظهر كأنه \"عالق\". كما يجب ملاحظة أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reason=\"length\"، مما يدل على أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لسياقها. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | يحصل أو يعيّن درجة حرارة العينة المستخدمة، بين 0 و 2. القيم الأعلى مثل 0.8 تجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 تجعلها أكثر تركيزًا وتحديدًا. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | يحصل أو يعيّن الموارد التي تستخدمها أدوات المساعد. الموارد خاصة بنوع الأداة. على سبيل المثال، أداة code_interpreter تتطلب قائمة بمعرفات الملفات، بينما أداة file_search تتطلب قائمة بمعرفات مخازن المتجهات. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | يحصل أو يعيّن قائمة بالأدوات المفعلة على المساعد. يمكن أن يكون هناك حد أقصى قدره 128 أداة لكل مساعد. يمكن أن تكون الأدوات من الأنواع code_interpreter أو file_search أو function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | يحصل أو يعيّن بديلاً للعينة باستخدام درجة الحرارة، يُسمى العينة النواة، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات كتلة الاحتمال top_p. لذا 0.1 يعني أن الرموز التي تشكل أعلى 10% من كتلة الاحتمال فقط تُؤخذ في الاعتبار. نوصي عمومًا بتعديل هذا أو درجة الحرارة ولكن ليس كليهما. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


