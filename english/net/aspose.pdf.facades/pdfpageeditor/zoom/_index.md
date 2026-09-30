---
title: "PdfPageEditor.Zoom"
linktitle: "Zoom"
articleTitle: "Zoom"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor property. Get or sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0. The following example demonstrates how to change z..."
type: docs
weight: 170
url: "/net/aspose.pdf.facades/pdfpageeditor/zoom/"
product_version: "26.9.0"
---
## PdfPageEditor.Zoom property

Get or sets zoom coefficient. Value 1.0 corresponds to 100%.
 Default value is 1.0.
 
 The following example demonstrates how to change zoom of the document pages.
 
 PdfPageEditor editor = new PdfPageEditor();
 editor.BindPdf("sample.pdf");
 editor.Zoom = 0.5f;

```csharp
public float Zoom { get; set; }
```

## Examples

The following example demonstrates how to change zoom of the document pages.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

### See Also

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

