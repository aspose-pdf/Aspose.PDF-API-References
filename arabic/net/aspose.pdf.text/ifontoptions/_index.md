---
title: "الواجهة IFontOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الواجهة Aspose.Pdf.Text.IFontOptions. خصائص مفيدة لضبط سلوك الخط"
type: docs
weight: 10790
url: /ar/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

خصائص مفيدة لضبط سلوك Font

```csharp
public interface IFontOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | أحيانًا لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب، مثل قيود الترخيص أو عندما لا يتم العثور على الخط المطلوب على جهاز الوجهة. عندما يحدث هذا الوضع ليس من السهل اكتشافه، لأن الخط المطلوب يتم تضمينه عبر علم الخاصية Font.IsEmbedded = true؛ بالطبع يمكن قراءة هذه الخاصية فور تعيينها لكن ذلك ليس نهجًا مريحًا. العلم NotifyAboutFontEmbeddingError يفرض آلية استثناء للحالات التي يفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم، سيتم رمي استثناء من النوع [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). القيمة الافتراضية false. |

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


