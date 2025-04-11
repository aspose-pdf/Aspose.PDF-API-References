---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى
type: docs
weight: 440
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## طريقة PdfContentEditor.ReplaceImage

تستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي تم استبدال الصورة فيها. |
| index | Int32 | فهرس كائن الصورة الذي يجب استبداله. |
| imageFile | String | ملف الصورة الذي سيتم استخدامه للاستبدال. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)