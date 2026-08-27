---
title: "AssistantCreateRequest.ResponseFormat"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية AssistantCreateRequest. يحصل أو يضبط التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT4o GPT4 Turbo وجميع نماذج GPT3.5 Turbo منذ gpt3.5turbo1106. الضبط إلى النوع json_object يفعّل وضع JSON الذي يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. مهم عند استخدام وضع JSON أن تقوم أيضًا بإرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك قد يولد النموذج تدفقًا لا نهائيًا من المسافات البيضاء حتى يصل التوليد إلى حد الرموز مما ينتج طلبًا طويلًا ويبدو عالقًا. لاحظ أيضًا أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reasonlength الذي يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لسياقها."
type: docs
weight: 70
url: /ar/net/aspose.pdf.ai/assistantcreaterequest/responseformat/
---
## AssistantCreateRequest.ResponseFormat property

يحصل أو يعيّن التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، والذي يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا إرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد يولد النموذج تدفقًا لا نهائيًا من الفراغات حتى يصل التوليد إلى حد الرموز، مما ينتج طلبًا طويل الأمد ويظهر كأنه \"عالق\". كما يجب ملاحظة أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reason=\"length\"، مما يدل على أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لسياقها.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### انظر أيضًا

* class [ResponseFormat](../../responseformat/)
* class [AssistantCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


