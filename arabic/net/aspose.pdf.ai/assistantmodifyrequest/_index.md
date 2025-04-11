---
title: Class AssistantModifyRequest
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.AssistantModifyRequest. كائن الطلب لتعديل مساعد
type: docs
weight: 130
url: /ar/net/aspose.pdf.ai/assistantmodifyrequest/
---
## فئة AssistantModifyRequest

كائن الطلب لتعديل مساعد.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | يحصل على أو يحدد وصف المساعد. الحد الأقصى للطول هو 512 حرف. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | يحصل على أو يحدد التعليمات النظامية التي يستخدمها المساعد. الحد الأقصى للطول هو 256,000 حرف. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | يحصل على أو يحدد مجموعة من 16 زوج مفتاح-قيمة يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | يحصل على أو يحدد معرف النموذج الذي يجب استخدامه. يمكنك استخدام واجهة برمجة التطبيقات لقائمة النماذج لرؤية جميع نماذجك المتاحة، أو الاطلاع على نظرة عامة على النموذج لوصفها. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | يحصل على أو يحدد اسم المساعد. الحد الأقصى للطول هو 256 حرف. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | يحصل على أو يحدد التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. تعيين إلى { "type": "json_object" } يمكّن وضع JSON، الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا توجيه النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا لا ينتهي من المسافات البيضاء حتى يصل التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كانت finish_reason="length"، مما يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | يحصل على أو يحدد درجة حرارة العينة للاستخدام، بين 0 و 2. القيم الأعلى مثل 0.8 ستجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 ستجعلها أكثر تركيزًا وحتمية. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | يحصل على أو يحدد الموارد التي تستخدمها أدوات المساعد. الموارد محددة بنوع الأداة. على سبيل المثال، تتطلب أداة code_interpreter قائمة بمعرفات الملفات، بينما تتطلب أداة file_search قائمة بمعرفات مخازن المتجهات. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | يحصل على أو يحدد قائمة بالأدوات المفعلة على المساعد. يمكن أن يكون هناك حد أقصى من 128 أداة لكل مساعد. يمكن أن تكون الأدوات من أنواع code_interpreter أو file_search أو function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | يحصل على أو يحدد بديلاً لأخذ العينات مع درجة الحرارة، يسمى أخذ العينات النووي، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات كتلة الاحتمال top_p. لذا فإن 0.1 تعني أن الرموز التي تتكون من أعلى 10% من كتلة الاحتمال فقط هي التي تؤخذ في الاعتبار. نوصي عمومًا بتغيير هذا أو درجة الحرارة ولكن ليس كلاهما. |

### انظر أيضًا

* class [AssistantCreateRequest](../assistantcreaterequest/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)