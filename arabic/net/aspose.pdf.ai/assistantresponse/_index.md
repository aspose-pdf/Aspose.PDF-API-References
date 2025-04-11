---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.AssistantResponse. تمثل مساعدًا يمكنه استدعاء النموذج واستخدام الأدوات
type: docs
weight: 140
url: /ar/net/aspose.pdf.ai/assistantresponse/
---
## Class AssistantResponse

تمثل مساعدًا يمكنه استدعاء النموذج واستخدام الأدوات.

```csharp
public class AssistantResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | يحصل على أو يحدد الطابع الزمني Unix (بالثواني) لوقت إنشاء المساعد. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | يحصل على أو يحدد وصف المساعد. الحد الأقصى للطول هو 512 حرفًا. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل على أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل على أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل على أو يحدد معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل على أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل على أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | يحصل على أو يحدد المعرف، الذي يمكن الإشارة إليه في نقاط نهاية API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | يحصل على أو يحدد التعليمات النظامية التي يستخدمها المساعد. الحد الأقصى للطول هو 256,000 حرف. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | يحصل على أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم التي يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | يحصل على أو يحدد معرف النموذج الذي يجب استخدامه. يمكنك استخدام واجهة برمجة التطبيقات لقائمة النماذج لرؤية جميع نماذجك المتاحة، أو الاطلاع على نظرة عامة على النموذج لوصفها. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | يحصل على أو يحدد اسم المساعد. الحد الأقصى للطول هو 256 حرفًا. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | يحصل على أو يحدد نوع الكائن، الذي يكون دائمًا مساعدًا. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | يحصل على أو يحدد التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o وGPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. تعيين إلى { "type": "json_object" } يمكّن وضع JSON، الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا توجيه النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا لا ينتهي من المسافات البيضاء حتى تصل التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كان finish_reason="length"، مما يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | يحصل على أو يحدد درجة حرارة العينة التي يجب استخدامها، بين 0 و2. القيم الأعلى مثل 0.8 ستجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 ستجعلها أكثر تركيزًا وحتمية. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | يحصل على أو يحدد مجموعة من الموارد التي تستخدمها أدوات المساعد. الموارد محددة بنوع الأداة. على سبيل المثال، تتطلب أداة code_interpreter قائمة بمعرفات الملفات، بينما تتطلب أداة file_search قائمة بمعرفات مخازن المتجهات. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | يحصل على أو يحدد قائمة بالأدوات المفعلة على المساعد. يمكن أن يكون هناك حد أقصى من 128 أداة لكل مساعد. يمكن أن تكون الأدوات من أنواع code_interpreter أو file_search أو function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | يحصل على أو يحدد بديلاً لأخذ العينات مع درجة الحرارة، يسمى أخذ العينات النووي، حيث يأخذ النموذج في الاعتبار نتائج الرموز مع كتلة احتمال top_p. لذا فإن 0.1 تعني أن الرموز التي تتكون من أعلى 10% من كتلة الاحتمال فقط هي التي تؤخذ في الاعتبار. نوصي عمومًا بتغيير هذا أو درجة الحرارة ولكن ليس كلاهما. |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)