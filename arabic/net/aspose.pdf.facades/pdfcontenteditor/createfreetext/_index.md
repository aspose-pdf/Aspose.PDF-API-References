---
title: CreateFreeText
second_title: Aspose.PDF لمرجع .NET API
description: إنشاء تعليق توضيحي نصي مجاني في مستند PDF
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

إنشاء تعليق توضيحي نصي مجاني في مستند PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق التوضيحي الذي يحدد موقع التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي النصي. |

### أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
