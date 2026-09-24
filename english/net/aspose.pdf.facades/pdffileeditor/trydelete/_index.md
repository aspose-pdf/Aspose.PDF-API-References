---
title: "PdfFileEditor.TryDelete"
linktitle: "TryDelete"
articleTitle: "TryDelete"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Deletes pages specified by number array from input file, saves as a new Pdf file."
type: docs
weight: 120
url: "/net/aspose.pdf.facades/pdffileeditor/trydelete/"
product_version: "26.9.0"
---
## TryDelete(string, int[], string) {#trydelete}

Deletes pages specified by number array from input file, saves as a new Pdf file.

The TryDelete method is like the Delete method, except the TryDelete 
 method does not throw an exception if the operation fails.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input file path. |
| pageNumber | int[] | Index of page out of the input file. |
| outputFile | string | Output file path. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete_1}

Deletes pages specified by number array from input file, saves as a new Pdf file.

The TryDelete method is like the Delete method, except the TryDelete 
 method does not throw an exception if the operation fails.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| pageNumber | int[] | Index of page out of the input file. |
| outputStream | Stream | Output file stream. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

