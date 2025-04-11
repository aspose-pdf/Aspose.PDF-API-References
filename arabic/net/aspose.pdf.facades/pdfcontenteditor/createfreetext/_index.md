---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق نصي حر في مستند PDF
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## طريقة PdfContentEditor.CreateFreeText

تنشئ تعليق نصي حر في مستند PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء تعليق النص. |

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