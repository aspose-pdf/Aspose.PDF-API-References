---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ رابطًا إلى JavaScript في مستند PDF
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## طريقة PdfContentEditor.CreateJavaScriptLink

تنشئ رابطًا إلى JavaScript في مستند PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| code | String | كود JavaScript. |
| rect | Rectangle | المستطيل للنقر النشط. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| color | Color | لون المستطيل للنقر النشط. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)