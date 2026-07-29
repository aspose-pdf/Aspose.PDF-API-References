---
title: "PdfContentEditor.CreateMarkup"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليقا توضيحيًا في مستند PDF"
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

ينشئ تعليقة توصيف في مستند PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| type | Int32 | نوع التعليق التوضيحي. يمكن أن يكون 0 (تمييز), 1 (تسطير), 2 (شطب), 3 (متموج). |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| clr | Color | لون التعليق التوضيحي. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


