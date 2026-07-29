---
title: "PdfContentEditor.CreatePopup"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليق توضيحي منبثق في مستند PDF"
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

ينشئ تعليقة منبثقة في مستند PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| open | Boolean | علامة تحدد ما إذا كان يجب عرض التعليق التوضيحي المنبثق مفتوحًا في البداية. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


