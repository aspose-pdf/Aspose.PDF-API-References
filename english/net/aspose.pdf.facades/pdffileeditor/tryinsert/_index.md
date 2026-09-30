---
title: "PdfFileEditor.TryInsert"
linktitle: "TryInsert"
articleTitle: "TryInsert"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Inserts pages from an other file into the input Pdf file."
type: docs
weight: 100
url: "/net/aspose.pdf.facades/pdffileeditor/tryinsert/"
product_version: "26.9.0"
---
## TryInsert(string, int, string, int[], string) {#tryinsert}

Inserts pages from an other file into the input Pdf file.

The TryInsert method is like the Insert method, except the TryInsert 
 method does not throw an exception if the operation fails.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file. |
| insertLocation | Int32 | Insert position in input file. |
| portFile | String | Pages from the Pdf file. |
| pageNumber | Int32[] | The page number of the ported in portFile. |
| outputFile | String | Output Pdf file. |

### Return Value

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert_1}

Inserts pages from an other file into the input Pdf file.

The TryInsert method is like the Insert method, except the TryInsert 
 method does not throw an exception if the operation fails.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Stream of Pdf file. |
| insertLocation | Int32 | Insert position in input file. |
| portStream | Stream | Stream of Pdf file for pages. |
| pageNumber | Int32[] | The page number of the ported in portFile. |
| outputStream | Stream | Output Stream. |

### Return Value

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

