---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تستخرج مجموعة من مثيلات Link الموجودة في مستند PDF
type: docs
weight: 370
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## طريقة PdfContentEditor.ExtractLink

تستخرج مجموعة من مثيلات Link الموجودة في مستند PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### قيمة الإرجاع

مجموعة من كائنات Link

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### انظر أيضًا

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)