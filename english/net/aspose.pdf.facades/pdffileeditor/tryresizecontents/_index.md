---
title: TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Resizes contents of pages of the document.
type: docs
weight: 450
url: /net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Resizes contents of pages of the document.

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

### Remarks

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails.

### Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

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

### Remarks

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails.

### Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

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

### Remarks

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails.

### Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
