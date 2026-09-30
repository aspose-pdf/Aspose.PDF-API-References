---
title: "PdfPageEditor.GetPageBoxSize"
linktitle: "GetPageBoxSize"
articleTitle: "GetPageBoxSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Returns size of specified box in document."
type: docs
weight: 70
url: "/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/"
product_version: "26.9.0"
---
## PdfPageEditor.GetPageBoxSize method

Returns size of specified box in document.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | Page index. Document pages are numbered from 1. |
| pageBoxName | String | Box type name. Valid values are: "art", "bleed", "crop", "media", "trim". |

### Return Value

Rectangle which contains requested box.

## Examples

The following example demonstrates how to get media box of the 1st page:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

