---
title: IFontOptions
second_title: Aspose.PDF لمرجع .NET API
description: خصائص مفيدة لضبط سلوك الخط
type: docs
weight: 6790
url: /ar/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

خصائص مفيدة لضبط سلوك الخط

```csharp
public interface IFontOptions
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror) { get; set; } | أحيانًا لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب ، على سبيل المثال قيود الترخيص أو عندما لم يتم العثور على الخط المطلوب على الكمبيوتر الوجهة . عندما يأتي هذا الموقف ، لا يتم الاكتشاف ببساطة ، لأن الخط المطلوب مضمن عبر مجموعة من علامة الخاصية Font.IsEmbedded = true بالطبع من الممكن قراءة هذه الخاصية فور ضبطها ولكن إنها ليست طريقة ملائمة. تفرض العلامة NotifyAboutFontEmbeddingError آلية الاستثناء للحالات التي فشلت فيها محاولة تضمين الخط. إذا تم تعيين هذه العلامة استثناء من type [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception) سوف يتم إلقاؤها. افتراضيا false . |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
