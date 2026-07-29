---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية IFontOptions. في بعض الأحيان لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب مثل قيود الترخيص أو عدم العثور على الخط المطلوب على جهاز الوجهة. عندما يحدث هذا الوضع لا يكون من السهل اكتشافه لأن الخط المطلوب يتم تضمينه عبر علم الخاصية Font.IsEmbedded = true. بالطبع يمكن قراءة هذه الخاصية فور تعيينها لكن ذلك ليس نهجًا مريحًا. علم NotifyAboutFontEmbeddingError يفرض آلية استثناء للحالات التي يفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم سيتم رمي استثناء من النوع FontEmbeddingException. القيمة الافتراضية false"
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

في بعض الأحيان لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب، مثل قيود الترخيص أو عدم العثور على الخط المطلوب على جهاز الوجهة. عندما يحدث هذا الوضع لا يكون من السهل اكتشافه، لأن الخط المطلوب يتم تضمينه عبر علم الخاصية Font.IsEmbedded = true؛ بالطبع يمكن قراءة هذه الخاصية فور تعيينها لكن ذلك ليس نهجًا مريحًا. علم NotifyAboutFontEmbeddingError يفرض آلية استثناء للحالات التي يفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم سيتم رمي استثناء من النوع [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). القيمة الافتراضية false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### انظر أيضًا

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


