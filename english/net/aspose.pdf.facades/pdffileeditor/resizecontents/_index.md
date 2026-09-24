---
title: "PdfFileEditor.ResizeContents"
linktitle: "ResizeContents"
articleTitle: "ResizeContents"
second_title: "Aspose.PDF for .NET"
description: ""
type: docs
weight: 870
url: "/net/aspose.pdf.facades/pdffileeditor/resizecontents/"
product_version: "26.9.0"
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}



```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, ContentsResizeParameters parameters)
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

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Resizes contents of document pages. 
 Shrinks contents of page and adds margins.
 New size of contents is specified in default space units.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, double newHeight)
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
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | string | Path to source document. |
| destination | string | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

### Return Value

bool

true if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_3}



```csharp
public bool ResizeContents(string source, string destination, int[] pages, ContentsResizeParameters parameters)
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

---

## ResizeContents([Document](../../../aspose.pdf/document/), int[], ContentsResizeParameters) {#resizecontents_4}



```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Document |  |
| pages | int[] |  |
| parameters | ContentsResizeParameters |  |

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents([Document](../../../aspose.pdf/document/), ContentsResizeParameters) {#resizecontents_5}



```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Document |  |
| parameters | ContentsResizeParameters |  |

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

