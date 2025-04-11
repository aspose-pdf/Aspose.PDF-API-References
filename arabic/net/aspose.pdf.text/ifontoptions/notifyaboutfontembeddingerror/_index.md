---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: خاصية IFontOptions. أحيانًا لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب، على سبيل المثال قيود الترخيص أو عندما لا يتم العثور على الخط المطلوب على الكمبيوتر الوجهة. عندما تحدث هذه الحالة، ليس من السهل اكتشافها، لأن الخط المطلوب يتم تضمينه عبر مجموعة من علم الخاصية Font.IsEmbedded = true; بالطبع، من الممكن قراءة هذه الخاصية مباشرة بعد تعيينها، ولكنها ليست طريقة مريحة. علم NotifyAboutFontEmbeddingError يفرض آلية استثناء للحالات التي تفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم، سيتم طرح استثناء من نوع [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). بشكل افتراضي false.
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## خاصية IFontOptions.NotifyAboutFontEmbeddingError

أحيانًا لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب، على سبيل المثال قيود الترخيص أو عندما لا يتم العثور على الخط المطلوب على الكمبيوتر الوجهة. عندما تحدث هذه الحالة، ليس من السهل اكتشافها، لأن الخط المطلوب يتم تضمينه عبر مجموعة من علم الخاصية Font.IsEmbedded = true; بالطبع، من الممكن قراءة هذه الخاصية مباشرة بعد تعيينها، ولكنها ليست طريقة مريحة. علم NotifyAboutFontEmbeddingError يفرض آلية استثناء للحالات التي تفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم، سيتم طرح استثناء من نوع [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). بشكل افتراضي false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### انظر أيضًا

* واجهة [IFontOptions](../)
* مساحة الاسم [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../../)