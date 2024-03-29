---
title: CreateSquareCircle
second_title: Aspose.PDF لمرجع .NET API
description: إنشاء تعليق توضيحي على شكل دائرة مربعة .
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

إنشاء تعليق توضيحي على شكل دائرة مربعة .

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق التوضيحي الذي يحدد موقع التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| clr | Color | لون المربع أو الدائرة. |
| square | Boolean | صحيح (مربع) ، خطأ (دائرة). |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي. |
| borderWidth | Int32 | عرض حدود المربع أو الدائرة. |

### أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
