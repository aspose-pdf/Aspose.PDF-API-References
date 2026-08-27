---
title: "الفئة AssistantResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.AssistantResponse. تمثل مساعدًا يمكنه استدعاء النموذج واستخدام الأدوات."
type: docs
weight: 140
url: /ar/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

يمثل مساعدًا يمكنه استدعاء النموذج واستخدام الأدوات.

```csharp
public class AssistantResponse : BaseResponse
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | يحصل أو يعيّن الطابع الزمني Unix (بالثواني) للوقت الذي تم فيه إنشاء المساعد. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | يحصل أو يعيّن وصف المساعد. الحد الأقصى للطول هو 512 حرفًا. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | يحصل أو يعيّن المعرف، الذي يمكن الإشارة إليه في نقاط النهاية API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | يحصل أو يعيّن تعليمات النظام التي يستخدمها المساعد. الحد الأقصى للطول هو 256,000 حرف. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | يحصل أو يعيّن معرّف النموذج المراد استخدامه. يمكنك استخدام واجهة برمجة تطبيقات List models لرؤية جميع النماذج المتاحة لديك، أو الاطلاع على نظرة عامة على النماذج للحصول على أوصافها. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | يحصل أو يعيّن اسم المساعد. الحد الأقصى للطول هو 256 حرفًا. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | يحصل أو يعيّن نوع الكائن، والذي يكون دائماً assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | يحصل أو يعيّن التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، والذي يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا إرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد يولد النموذج تدفقًا لا نهائيًا من الفراغات حتى يصل التوليد إلى حد الرموز، مما ينتج طلبًا طويل الأمد ويظهر كأنه \"عالق\". كما يجب ملاحظة أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reason=\"length\"، مما يدل على أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لسياقها. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة، بين 0 و 2. القيم الأعلى مثل 0.8 تجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 تجعلها أكثر تركيزًا وحتمية. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | يحصل أو يعيّن مجموعة من الموارد التي تستخدمها أدوات المساعد. الموارد محددة بنوع الأداة. على سبيل المثال، أداة code_interpreter تتطلب قائمة بمعرّفات الملفات، بينما أداة file_search تتطلب قائمة بمعرّفات المتاجر المتجهة. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | يحصل أو يعيّن قائمة بالأدوات المفعلة على المساعد. يمكن أن يكون هناك حد أقصى قدره 128 أداة لكل مساعد. يمكن أن تكون الأدوات من الأنواع code_interpreter أو file_search أو function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | يحصل أو يعيّن بديلاً للعينة باستخدام درجة الحرارة، يُسمى العينة النواة، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات كتلة الاحتمال top_p. لذا 0.1 يعني أن الرموز التي تشكل أعلى 10% من كتلة الاحتمال فقط تُؤخذ في الاعتبار. نوصي عمومًا بتعديل هذا أو درجة الحرارة ولكن ليس كليهما. |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


