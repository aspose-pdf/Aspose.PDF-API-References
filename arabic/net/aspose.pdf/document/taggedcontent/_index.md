---
title: "Document.TaggedContent"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Document property. يحصل على الوصول إلى محتوى TaggedPdf"
type: docs
weight: 540
url: /ar/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

يحصل على الوصول إلى محتوى TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## أمثلة

يوضح المثال كيفية استخدام المحتوى الموسوم لإنشاء مستند جديد يحتوي على رأس وفقرة وصور.

```csharp
// إنشاء مستند جديد
Document document = new Document();

// احصل على المحتوى الموسوم
ITaggedContent taggedContent = document.TaggedContent;

// تعيين اللغة للمستند
taggedContent.SetLanguage("en-US");

// تعيين العنوان لمستند PDF
taggedContent.SetTitle("Example document");

// إنشاء وإضافة القسم
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// إنشاء رأس
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// إنشاء فقرة
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// إنشاء توضيح
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// حفظ المستند
document.Save("example.pdf");
```

### انظر أيضًا

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


