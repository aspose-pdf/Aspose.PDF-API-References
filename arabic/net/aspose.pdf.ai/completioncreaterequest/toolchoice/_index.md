---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: خاصية CompletionCreateRequest. تحصل أو تعين كائنًا يتحكم في أي أداة إن وجدت يتم استدعاؤها بواسطة النموذج. تعني none أن النموذج لن يستدعي أي أداة وبدلاً من ذلك يولد رسالة. تعني auto أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. تعني required أن النموذج يجب أن يستدعي أداة أو أكثر. تحديد أداة معينة عبر {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة. none هو الإعداد الافتراضي عندما لا توجد أدوات. auto هو الإعداد الافتراضي إذا كانت الأدوات موجودة.
type: docs
weight: 150
url: /ar/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## خاصية CompletionCreateRequest.ToolChoice

تحصل أو تعين كائنًا يتحكم في أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. تعني none أن النموذج لن يستدعي أي أداة وبدلاً من ذلك يولد رسالة. تعني auto أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. تعني required أن النموذج يجب أن يستدعي أداة أو أكثر. تحديد أداة معينة عبر {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة. none هو الإعداد الافتراضي عندما لا توجد أدوات. auto هو الإعداد الافتراضي إذا كانت الأدوات موجودة.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### انظر أيضًا

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)