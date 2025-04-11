---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق مربع دائري
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## طريقة PdfContentEditor.CreateSquareCircle

تنشئ تعليق مربع دائري.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| clr | Color | لون المربع أو الدائرة. |
| square | Boolean | صحيح (مربع)، خطأ (دائرة). |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| borderWidth | Int32 | عرض حدود المربع أو الدائرة. |

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