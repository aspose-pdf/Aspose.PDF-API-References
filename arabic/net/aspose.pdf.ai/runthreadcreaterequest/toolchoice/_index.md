---
title: "RunThreadCreateRequest.ToolChoice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية RunThreadCreateRequest. تحصل أو تعين أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none تعني أن النموذج لن يستدعي أي أدوات وبدلاً من ذلك يولد رسالة. auto هي القيمة الافتراضية وتعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required تعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل type file_search أو type function function name my_function يجبر النموذج على استدعاء تلك الأداة"
type: docs
weight: 120
url: /ar/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice property

يحصل أو يعيّن أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none يعني أن النموذج لن يستدعي أي أدوات بل سيولد رسالة بدلاً من ذلك. auto هو القيمة الافتراضية ويعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required يعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {\"type\": \"file_search\"} أو {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} يجبر النموذج على استدعاء تلك الأداة.

```csharp
public string ToolChoice { get; set; }
```

### انظر أيضًا

* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


