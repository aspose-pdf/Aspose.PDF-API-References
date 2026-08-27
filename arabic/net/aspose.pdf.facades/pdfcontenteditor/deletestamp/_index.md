---
title: "PdfContentEditor.DeleteStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "PdfContentEditor method. يحذف عدة طوابع على الصفحة المحددة حسب فهارس الطوابع"
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

يحذف عدة طوابع في الصفحة المحددة حسب فهارس الطوابع.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي سيتم حذف الختم منها. |
| index | Int32[] | فهارس الطوابع. |

## أمثلة

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


