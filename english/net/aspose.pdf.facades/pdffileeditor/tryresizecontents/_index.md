---
title: "PdfFileEditor.TryResizeContents"
linktitle: "TryResizeContents"
articleTitle: "TryResizeContents"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Resizes contents of pages of the document."
type: docs
weight: 370
url: "/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/"
product_version: "26.9.0"
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Resizes contents of pages of the document.

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents 
 method does not throw an exception if the operation fails.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream with source document. |
| destination | Stream | Stream with the destination document. |
| pages | Int32[] | Array of page indexes. |
| parameters | ContentsResizeParameters | Resize parameters. |

### Return Value

Returns true if success.

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
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | Double | New width of page contents in default space units. |
| newHeight | Double | New height of page contents in default space units. |

### Return Value

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents 
 method does not throw an exception if the operation fails.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Source document path. |
| destination | String | Destination document path. |
| pages | Int32[] | Array of page indexes (page index starts from 1). |
| parameters | ContentsResizeParameters | Parameters of page resize. |

### Return Value

true if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

