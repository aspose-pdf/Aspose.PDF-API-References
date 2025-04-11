---
title: AssistantResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: خاصية AssistantResponse. تحصل أو تعين التنسيق الذي يجب أن يخرجه النموذج. متوافق مع GPT4o و GPT4 Turbo وجميع نماذج GPT3.5 Turbo منذ gpt3.5turbo1106. تعيين إلى  type json_object  يمكّن وضع JSON الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. من المهم عند استخدام وضع JSON أن instruct النموذج أيضًا لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا لا نهاية له من المسافات البيضاء حتى تصل عملية التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كانت finish_reasonlength تشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق.
type: docs
weight: 100
url: /ar/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## خاصية AssistantResponse.ResponseFormat

تحصل أو تعين التنسيق الذي يجب أن يخرجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. تعيين إلى { "type": "json_object" } يمكّن وضع JSON، الذي يضمن أن الرسالة التي ينتجها النموذج هي JSON صالح. من المهم: عند استخدام وضع JSON، يجب عليك أيضًا instruct النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد ينتج النموذج تدفقًا لا نهاية له من المسافات البيضاء حتى تصل عملية التوليد إلى حد الرموز، مما يؤدي إلى طلب طويل الأمد ويبدو "عالقًا". لاحظ أيضًا أن محتوى الرسالة قد يتم قطعه جزئيًا إذا كانت finish_reason="length"، مما يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### انظر أيضًا

* class [ResponseFormat](../../responseformat/)
* class [AssistantResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)