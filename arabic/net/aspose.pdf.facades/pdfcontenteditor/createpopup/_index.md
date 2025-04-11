---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق منبثق في مستند PDF
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## طريقة PdfContentEditor.CreatePopup

تنشئ تعليق منبثق في مستند PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| open | Boolean | علامة تحدد ما إذا كان يجب عرض التعليق المنبثق مفتوحًا في البداية. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |

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