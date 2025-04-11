---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.CreateEmbeddingRequest. تمثل طلبًا لنقطة نهاية إنشاء التضمينات
type: docs
weight: 260
url: /ar/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

تمثل طلبًا لنقطة نهاية إنشاء التضمينات.

```csharp
public class CreateEmbeddingRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | يحصل أو يحدد عدد الأبعاد التي يجب أن تحتوي عليها التضمينات الناتجة. مدعوم فقط في النماذج text-embedding-3 وما بعدها. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | يحصل أو يحدد التنسيق لإرجاع التضمينات. يمكن أن يكون إما float أو base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | يحصل أو يحدد نص الإدخال للتضمين، مشفر كسلسلة أو مصفوفة من الرموز. لتضمين مدخلات متعددة في طلب واحد، مرر مصفوفة من السلاسل أو مصفوفة من مصفوفات الرموز. يجب ألا يتجاوز الإدخال الحد الأقصى لرموز الإدخال للنموذج (8192 رمز للنموذج text-embedding-ada-002)، ولا يمكن أن يكون سلسلة فارغة، ويجب أن تكون أي مصفوفة 2048 بعدًا أو أقل. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | يحصل أو يحدد النموذج لإنشاء التضمين له. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | يحصل أو يحدد معرفًا فريدًا يمثل المستخدم النهائي الخاص بك، مما يمكن أن يساعد OpenAI في مراقبة واكتشاف الإساءة. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)