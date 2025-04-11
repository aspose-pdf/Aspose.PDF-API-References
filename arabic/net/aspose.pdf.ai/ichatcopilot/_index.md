---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: واجهة Aspose.Pdf.AI.IChatCopilot. تمثل مساعد دردشة للتفاعل مع الوثائق عبر نماذج الذكاء الاصطناعي
type: docs
weight: 470
url: /ar/net/aspose.pdf.ai/ichatcopilot/
---
## واجهة IChatCopilot

تمثل مساعد دردشة للتفاعل مع الوثائق عبر نماذج الذكاء الاصطناعي.

```csharp
public interface IChatCopilot : IAICopilot
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | يحذف السياق بشكل غير متزامن. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | يحصل بشكل غير متزامن على استجابة لقائمة الرسائل المعطاة. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | يحصل بشكل غير متزامن على استجابة للرسالة المعطاة. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | يحفظ السياق بشكل غير متزامن إلى ملف JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | يحفظ الاستجابات لقائمة الرسائل المعطاة بشكل غير متزامن إلى ملف PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | يحفظ الاستجابة للرسالة المعطاة بشكل غير متزامن إلى ملف PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | يحفظ الاستجابات لقائمة الرسائل المعطاة بشكل غير متزامن إلى ملف بالتنسيق المحدد. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | يحفظ الاستجابة للرسالة المعطاة بشكل غير متزامن إلى ملف بالتنسيق المحدد. |

### انظر أيضًا

* واجهة [IAICopilot](../iaicopilot/)
* مساحة الأسماء [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* التجميع [Aspose.PDF](../../)