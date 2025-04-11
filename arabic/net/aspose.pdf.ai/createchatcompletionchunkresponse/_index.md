---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.CreateChatCompletionChunkResponse. تمثل جزءًا متدفقًا من استجابة إكمال الدردشة التي تم إرجاعها بواسطة النموذج بناءً على الإدخال المقدم
type: docs
weight: 250
url: /ar/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

تمثل جزءًا متدفقًا من استجابة إكمال الدردشة التي تم إرجاعها بواسطة النموذج، بناءً على الإدخال المقدم.

```csharp
public class CreateChatCompletionChunkResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | يحصل أو يحدد قائمة بخيارات إكمال الدردشة. يمكن أن تحتوي على أكثر من عنصر واحد إذا كان n أكبر من 1. يمكن أن تكون فارغة أيضًا للجزء الأخير إذا قمت بتعيين stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء إكمال الدردشة. كل جزء له نفس الطابع الزمني. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | يحصل أو يحدد معرفًا فريدًا لإكمال الدردشة. كل جزء له نفس المعرف. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | يحصل أو يحدد النموذج لتوليد الإكمال. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، والذي يكون دائمًا chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | يحصل أو يحدد بصمة تمثل تكوين الخلفية الذي يعمل به النموذج. يمكن استخدامها مع معلمة طلب البذور لفهم متى تم إجراء تغييرات في الخلفية قد تؤثر على الحتمية. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | يحصل أو يحدد حقلًا اختياريًا سيكون موجودًا فقط عندما تقوم بتعيين stream_options: {"include_usage": true} في طلبك. عند وجوده، يحتوي على قيمة فارغة باستثناء الجزء الأخير الذي يحتوي على إحصائيات استخدام الرمز للطلب بالكامل. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)