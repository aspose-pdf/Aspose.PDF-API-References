---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق نصي في مستند PDF
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## طريقة PdfContentEditor.CreateText

تنشئ تعليق نصي في مستند PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| title | String | عنوان التعليق. |
| contents | String | محتويات التعليق. |
| open | Boolean | علامة تحدد ما إذا كان يجب عرض التعليق مفتوحًا في البداية. |
| icon | String | اسم أيقونة ستستخدم في عرض التعليق. يمكن أن تكون هذه القيمة: "Comment"، "Key"، "Note"، "Help"، "NewParagraph"، "Paragraph"، "Insert" |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق النصي. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)