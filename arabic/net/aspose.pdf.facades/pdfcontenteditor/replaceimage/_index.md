---
title: "PdfContentEditor.ReplaceImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى"
type: docs
weight: 440
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

يستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | عدد الصفحة التي تم استبدال الصورة فيها. |
| index | Int32 | فهرس كائن الصورة الذي يجب استبداله. |
| imageFile | String | سيتم استخدام ملف الصورة للاستبدال. |

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


