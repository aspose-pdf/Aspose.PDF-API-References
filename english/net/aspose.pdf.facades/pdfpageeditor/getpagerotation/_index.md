---
title: "PdfPageEditor.GetPageRotation"
linktitle: "GetPageRotation"
articleTitle: "GetPageRotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Returns the rotation of specified page."
type: docs
weight: 60
url: "/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/"
product_version: "26.9"
---
## PdfPageEditor.GetPageRotation method

Returns the rotation of specified page.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | Page index. Document pages are numbered from 1. |

### Return Value

Page rotation in degrees.

## Examples

The following example demonstrates how to get page rotation:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");
```

### See Also

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

