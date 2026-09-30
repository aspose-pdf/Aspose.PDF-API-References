---
title: "PdfFileEditor.ResizeContents"
linktitle: "ResizeContents"
articleTitle: "ResizeContents"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Resizes contents of pages of the document."
type: docs
weight: 870
url: "/net/aspose.pdf.facades/pdffileeditor/resizecontents/"
product_version: "26.9.0"
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Resizes contents of pages of the document.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
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

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Resizes contents of document pages. 
 Shrinks contents of page and adds margins.
 New size of contents is specified in default space units.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

True if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_2}

Resizes contents of document pages. 
 Shrinks contents of page and adds margins.
 New size of contents is specified in default space units.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Path to source document. |
| destination | String | Path where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | Double | New width of page contents in default space units. |
| newHeight | Double | New height of page contents in default space units. |

### Return Value

true if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_3}

Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
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

---

## ResizeContents([Document](../../../aspose.pdf/document/), int[], ContentsResizeParameters) {#resizecontents_4}

Resizes pages of document. Blank margins are added around of shrinked page.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Document | Source document. |
| pages | Int32[] | List of page indexes. |
| parameters | ContentsResizeParameters | Resize parameters. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents([Document](../../../aspose.pdf/document/), ContentsResizeParameters) {#resizecontents_5}

Resizes pages of document. Blank margins are added around of shrinked page.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Document | Source document. |
| parameters | ContentsResizeParameters | Resize parameters. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

