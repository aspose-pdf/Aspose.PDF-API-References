---
title: RunThreadCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: خاصية RunThreadCreateRequest. تحصل أو تضبط أي أداة يتم استدعاؤها بواسطة النموذج. تعني none أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك يولد رسالة. auto هي القيمة الافتراضية وتعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {"type": "file_search"} أو {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة.
type: docs
weight: 120
url: /ar/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## خاصية RunThreadCreateRequest.ToolChoice

تحصل أو تضبط أي (إذا كانت موجودة) أداة يتم استدعاؤها بواسطة النموذج. تعني none أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك يولد رسالة. auto هي القيمة الافتراضية وتعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {"type": "file_search"} أو {"type": "function", "function": {"name": "my_function"}} يجبر النموذج على استدعاء تلك الأداة.

```csharp
public string ToolChoice { get; set; }
```

### انظر أيضًا

* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)