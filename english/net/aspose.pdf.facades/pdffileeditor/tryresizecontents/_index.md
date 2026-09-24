---
title: "PdfFileEditor.TryResizeContents"
linktitle: "TryResizeContents"
articleTitle: "TryResizeContents"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method."
type: docs
weight: 370
url: "/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/"
product_version: "26.9.0"
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}



```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream |  |
| destination | Stream |  |
| pages | int[] |  |
| parameters | ContentsResizeParameters |  |

### Return Value

bool

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Resizes contents of document pages. 
 Shrinks contents of page and adds margins.
 New size of contents is specified in default space units.

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents 
 method does not throw an exception if the operation fails.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}



```csharp
public bool TryResizeContents(string source, string destination, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | string |  |
| destination | string |  |
| pages | int[] |  |
| parameters | ContentsResizeParameters |  |

### Return Value

bool

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

