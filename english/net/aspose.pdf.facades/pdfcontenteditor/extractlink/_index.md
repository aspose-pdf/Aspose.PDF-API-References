---
title: ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: Extracts the collection of Link instances contained in PDF document.
type: docs
weight: 370
url: /net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Extracts the collection of Link instances contained in PDF document.

```csharp
public IList<Annotation> ExtractLink()
```

### Return Value

The collection of Link objects

### Examples

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

### See Also

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfContentEditor](../../pdfcontenteditor)
* namespace [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->