---
title: "RunCreateRequest.ToolChoice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية RunCreateRequest. يحصل أو يضبط أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none يعني أن النموذج لن يستدعي أي أدوات بل سيولد رسالة. auto هو القيمة الافتراضية ويعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required يعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل النوع file_search أو النوع function باسم الدالة my_function يجبر النموذج على استدعاء تلك الأداة."
type: docs
weight: 130
url: /ar/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice property

يحصل أو يعيّن أي أداة (إن وجدت) يتم استدعاؤها بواسطة النموذج. none يعني أن النموذج لن يستدعي أي أدوات بل سيولد رسالة بدلاً من ذلك. auto هو القيمة الافتراضية ويعني أن النموذج يمكنه الاختيار بين توليد رسالة أو استدعاء أداة أو أكثر. required يعني أن النموذج يجب أن يستدعي أداة أو أكثر قبل الرد على المستخدم. تحديد أداة معينة مثل {\"type\": \"file_search\"} أو {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} يجبر النموذج على استدعاء تلك الأداة.

```csharp
public string ToolChoice { get; set; }
```

### انظر أيضًا

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


