---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تُنشئ تعليقة مربع أو دائرة"
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

ينشئ تعليقة مربع-دائرة.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| clr | Color | لون المربع أو الدائرة. |
| مربع | Boolean | صحيح (مربع), خطأ (دائرة). |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| borderWidth | Int32 | عرض الحدود للمربع أو الدائرة. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


