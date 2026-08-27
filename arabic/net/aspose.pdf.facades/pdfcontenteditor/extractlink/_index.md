---
title: "PdfContentEditor.ExtractLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تستخرج مجموعة كائنات Link الموجودة في مستند PDF"
type: docs
weight: 370
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

يستخرج مجموعة كائنات الرابط الموجودة في مستند PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### قيمة الإرجاع

مجموعة كائنات Link

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // العمل مع كائن Link
}
```

### انظر أيضًا

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


