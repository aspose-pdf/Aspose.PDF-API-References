---
title: "الفئة CreateChatCompletionChunkResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.CreateChatCompletionChunkResponse. تمثل جزءًا متدفقًا من استجابة إكمال الدردشة التي يُرجعها النموذج بناءً على الإدخال المقدم."
type: docs
weight: 260
url: /ar/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

يمثل جزءًا متدفقًا من استجابة إكمال محادثة تُرجعها النموذج، بناءً على الإدخال المقدم.

```csharp
public class CreateChatCompletionChunkResponse
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | يحصل أو يعيّن قائمة من خيارات إكمال الدردشة. يمكن أن تحتوي على أكثر من عنصر إذا كان n أكبر من 1. يمكن أن تكون فارغة أيضًا للجزء الأخير إذا قمت بتعيين stream_options: {\"include_usage\": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | يحصل أو يعيّن الطابع الزمني Unix (بالثواني) للوقت الذي تم فيه إنشاء إكمال الدردشة. كل جزء له نفس الطابع الزمني. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | يحصل أو يعيّن معرفًا فريدًا لإكمال الدردشة. كل جزء له نفس المعرف. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | يحصل أو يعيّن النموذج لتوليد الإكمال. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | يحصل أو يعيّن نوع الكائن، والذي يكون دائمًا chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | يحصل أو يعيّن البصمة التي تمثل تكوين الواجهة الخلفية التي يعمل بها النموذج. يمكن استخدامها بالاشتراك مع معامل طلب البذرة لفهم متى تم إجراء تغييرات على الواجهة الخلفية قد تؤثر على الحتمية. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | يحصل أو يعيّن حقلًا اختياريًا سيكون موجودًا فقط عندما تقوم بتعيين stream_options: {"include_usage": true} في طلبك. عندما يكون موجودًا، يحتوي على قيمة فارغة باستثناء الجزء الأخير الذي يحتوي على إحصائيات استخدام الرموز للطلب بأكمله. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


