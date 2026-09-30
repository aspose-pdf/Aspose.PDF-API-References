---
title: "PdfFileEditor.TryAppend"
linktitle: "TryAppend"
articleTitle: "TryAppend"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams..."
type: docs
weight: 80
url: "/net/aspose.pdf.facades/pdffileeditor/tryappend/"
product_version: "26.9.0"
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Appends pages, which are chosen from array of documents in portStreams.
 The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

The TryAppend method is like the Append method, except the TryAppend 
 method does not throw an exception if the operation fails.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Pdf stream. |
| portStreams | Stream[] | Documents to copy pages from. |
| startPage | Int32 | Page starts in portStreams documents. |
| endPage | Int32 | Page ends in portStreams documents . |
| outputStream | Stream | Output Pdf stream. |

### Return Value

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Appends pages, which are chosen from portFiles documents. 
 The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

The TryAppend method is like the Append method, except the TryAppend 
 method does not throw an exception if the operation fails.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file. |
| portFiles | String[] | Documents to copy pages from. |
| startPage | Int32 | Page starts in portFiles documents. |
| endPage | Int32 | Page ends in portFiles documents . |
| outputFile | String | Output Pdf document. |

### Return Value

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

