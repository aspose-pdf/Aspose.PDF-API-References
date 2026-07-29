---
title: "الفئة CreateEmbeddingRequest"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.CreateEmbeddingRequest. تمثل طلبًا لنقطة النهاية Create Embeddings"
type: docs
weight: 270
url: /ar/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

يمثل طلبًا لنقطة النهاية Create Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | يحصل أو يضبط عدد الأبعاد التي يجب أن تحتويها المخرجات المتجهة الناتجة. يدعم فقط في نماذج text-embedding-3 وما بعدها. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | يحصل أو يضبط الصيغة التي تُرجع بها المتجهات. يمكن أن تكون إما float أو base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | يحصل أو يضبط نص الإدخال لتضمينه، مُشفّر كسلسلة أو مصفوفة من الرموز. لتضمين مدخلات متعددة في طلب واحد، مرّر مصفوفة من السلاسل أو مصفوفة من مصفوفات الرموز. يجب ألا يتجاوز الإدخال الحد الأقصى لعدد الرموز للنموذج (8192 رمزًا لـ text-embedding-ada-002)، ولا يمكن أن يكون سلسلة فارغة، ويجب أن تكون أي مصفوفة بحد أقصى 2048 بُعد أو أقل. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | يحصل أو يضبط النموذج الذي يُولَّد المتجه من أجله. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | يحصل أو يضبط معرّفًا فريدًا يمثل المستخدم النهائي الخاص بك، مما يمكن OpenAI من مراقبة واكتشاف الإساءة. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


