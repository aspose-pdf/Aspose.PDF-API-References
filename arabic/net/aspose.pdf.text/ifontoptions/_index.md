---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: واجهة Aspose.Pdf.Text.IFontOptions. خصائص مفيدة لضبط سلوك الخط
type: docs
weight: 10610
url: /ar/net/aspose.pdf.text/ifontoptions/
---
## واجهة IFontOptions

خصائص مفيدة لضبط سلوك الخط

```csharp
public interface IFontOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | أحيانًا لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب، مثل قيود الترخيص أو عندما لا يتم العثور على الخط المطلوب على الكمبيوتر الوجهة. عندما تحدث هذه الحالة، ليس من السهل اكتشافها، لأن الخط المطلوب مضمن عبر مجموعة من خاصية العلم Font.IsEmbedded = true; بالطبع، من الممكن قراءة هذه الخاصية مباشرة بعد تعيينها ولكنها ليست طريقة مريحة. العلم NotifyAboutFontEmbeddingError يفرض آلية الاستثناء للحالات التي تفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم، سيتم طرح استثناء من النوع [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). بشكل افتراضي false. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)