---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.AssistantCreateRequest. كائن الطلب لإنشاء مساعد
type: docs
weight: 100
url: /ar/net/aspose.pdf.ai/assistantcreaterequest/
---
## فئة AssistantCreateRequest

كائن الطلب لإنشاء مساعد.

```csharp
public class AssistantCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | يحصل أو يحدد وصف المساعد. الحد الأقصى للطول هو 512 حرفًا. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | يحصل أو يحدد التعليمات النظامية التي يستخدمها المساعد. الحد الأقصى للطول هو 256,000 حرف. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | يحصل أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | يحصل أو يحدد معرف النموذج الذي يجب استخدامه. يمكنك استخدام واجهة برمجة التطبيقات لقائمة النماذج لرؤية جميع نماذجك المتاحة، أو الاطلاع على نظرة عامة على النموذج لوصفها. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | يحصل أو يحدد اسم المساعد. الحد الأقصى للطول هو 256 حرفًا. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | يحصل أو يحدد التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106 . تعيين إلى { "type": "json_object" } يمكّن وضع JSON، الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا توجيه النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا غير منتهي من المسافات البيضاء حتى تصل التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كان finish_reason="length"، مما يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة للاستخدام، بين 0 و 2. القيم الأعلى مثل 0.8 ستجعل المخرجات أكثر عشوائية، بينما القيم الأقل مثل 0.2 ستجعلها أكثر تركيزًا وحتمية. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | يحصل أو يحدد الموارد التي تستخدمها أدوات المساعد. الموارد محددة بنوع الأداة. على سبيل المثال، تتطلب أداة code_interpreter قائمة بمعرفات الملفات، بينما تتطلب أداة file_search قائمة بمعرفات مخازن المتجهات. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | يحصل أو يحدد قائمة بالأدوات المفعلة على المساعد. يمكن أن يكون هناك حد أقصى يبلغ 128 أداة لكل مساعد. يمكن أن تكون الأدوات من أنواع code_interpreter أو file_search أو function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | يحصل أو يحدد بديلاً لأخذ العينات مع درجة الحرارة، يسمى أخذ العينات النواة، حيث يأخذ النموذج في الاعتبار نتائج الرموز ذات الكتلة الاحتمالية top_p. لذا فإن 0.1 تعني أن الرموز التي تتكون من أعلى 10% من الكتلة الاحتمالية فقط هي التي تؤخذ في الاعتبار. نوصي عمومًا بتغيير هذا أو درجة الحرارة ولكن ليس كلاهما. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* التجميع [Aspose.PDF](../../)