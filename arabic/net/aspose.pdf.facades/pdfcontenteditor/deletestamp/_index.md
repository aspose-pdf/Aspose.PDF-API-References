---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تحذف عدة طوابع على الصفحة المحددة بواسطة فهارس الطوابع
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## طريقة PdfContentEditor.DeleteStamp

تحذف عدة طوابع على الصفحة المحددة بواسطة فهارس الطوابع.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي سيتم حذف الطابع منها. |
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