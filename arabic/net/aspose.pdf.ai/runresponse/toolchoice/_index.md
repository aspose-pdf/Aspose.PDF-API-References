---
title: RunResponse.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: خاصية RunResponse. تحصل أو تعين أي أداة يتم استدعاؤها بواسطة النموذج. تعني none أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك يولد رسالة. auto هي القيمة الافتراضية وتعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل يجبر النموذج على استدعاء تلك الأداة.
type: docs
weight: 230
url: /ar/net/aspose.pdf.ai/runresponse/toolchoice/
---
## خاصية RunResponse.ToolChoice

تحصل أو تعين أي (إذا كانت موجودة) أداة يتم استدعاؤها بواسطة النموذج. تعني none أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك يولد رسالة. auto هي القيمة الافتراضية وتعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {"type": "file_search"} أو {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة.

```csharp
public string ToolChoice { get; set; }
```

### انظر أيضًا

* class [RunResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)