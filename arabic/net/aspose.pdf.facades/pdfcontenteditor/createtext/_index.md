---
title: "PdfContentEditor.CreateText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليقا نصيًا في مستند PDF"
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

ينشئ تعليقة نص في مستند PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| title | String | عنوان التعليق. |
| contents | String | محتوى التعليق التوضيحي. |
| open | Boolean | علامة تحدد ما إذا كان يجب عرض التعليق مفتوحًا مبدئيًا. |
| icon | String | سيتم استخدام اسم أيقونة عند عرض التعليق. يمكن أن تكون هذه القيمة: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| صفحة | Int32 | رقم الصفحة الأصلية التي سيتم إنشاء التعليق النصي فيها. |

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


