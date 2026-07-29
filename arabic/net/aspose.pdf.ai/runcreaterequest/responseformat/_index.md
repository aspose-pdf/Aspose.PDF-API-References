---
title: "RunCreateRequest.ResponseFormat"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية RunCreateRequest. يحصل أو يضبط تنسيق الاستجابة. يحدد التنسيق الذي يجب على النموذج إخراجه. متوافق مع نماذج GPT4o و GPT4 Turbo وجميع نماذج GPT3.5 Turbo منذ gpt3.5turbo1106. الضبط إلى type json_object يفعّل وضع JSON الذي يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. مهم عند استخدام وضع JSON أن تُعطي النموذج تعليمات لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك قد يولد النموذج تدفقًا لا نهائيًا من الفراغ حتى يصل التوليد إلى حد الرموز مما ينتج طلبًا طويلًا يبدو عالقًا. كما أن محتوى الرسالة قد يُقطع جزئيًا إذا كان finish_reasonlength الذي يشير إلى أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق."
type: docs
weight: 100
url: /ar/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat property

يحصل أو يعيّن تنسيق الاستجابة. يحدد التنسيق الذي يجب أن ينتجه النموذج. متوافق مع GPT-4o و GPT-4 Turbo وجميع نماذج GPT-3.5 Turbo منذ gpt-3.5-turbo-1106. الضبط إلى { \"type\": \"json_object\" } يفعّل وضع JSON، والذي يضمن أن الرسالة التي يولدها النموذج هي JSON صالح. مهم: عند استخدام وضع JSON، يجب عليك أيضًا إرشاد النموذج لإنتاج JSON بنفسك عبر رسالة نظام أو مستخدم. بدون ذلك، قد يولد النموذج تدفقًا لا نهائيًا من المسافات البيضاء حتى يصل التوليد إلى حد الرموز، مما ينتج طلبًا طويلًا ويبدو \"عالقًا\". أيضًا لاحظ أن محتوى الرسالة قد يُقطَع جزئيًا إذا كان finish_reason=\"length\"، مما يدل على أن التوليد تجاوز max_tokens أو أن المحادثة تجاوزت الحد الأقصى لطول السياق.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### انظر أيضًا

* class [ResponseFormat](../../responseformat/)
* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


