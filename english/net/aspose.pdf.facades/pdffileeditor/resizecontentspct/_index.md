---
title: "PdfFileEditor.ResizeContentsPct"
linktitle: "ResizeContentsPct"
articleTitle: "ResizeContentsPct"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents."
type: docs
weight: 890
url: "/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/"
product_version: "26.9.0"
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Resizes contents of document pages.
 Shrinks contents of page and adds margins.
 New contents size is specified in percents.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | Double | New width of page contents in percents. |
| newHeight | Double | New height of page contents in percetns. |

### Return Value

true if resized sucessfully.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Resizes contents of document pages.
 Shrinks contents of page and adds margins.
 New contents size is specified in percents.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Path to source document. |
| destination | String | Path where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | Double | New width of page contents in percents. |
| newHeight | Double | New height of page contents in percetns. |

### Return Value

true if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

