---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ رابطًا إلى JavaScript في مستند PDF"
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

ينشئ رابطًا إلى JavaScript في مستند PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الرمز | String | كود JavaScript. |
| rect | Rectangle | المستطيل للنقر النشط. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
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


