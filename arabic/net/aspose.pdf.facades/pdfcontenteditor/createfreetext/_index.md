---
title: "PdfContentEditor.CreateFreeText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليقا نصيًا حرًا في مستند PDF"
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

ينشئ تعليقة نص حر في مستند PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| صفحة | Int32 | رقم الصفحة الأصلية التي سيتم إنشاء التعليق النصي فيها. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


