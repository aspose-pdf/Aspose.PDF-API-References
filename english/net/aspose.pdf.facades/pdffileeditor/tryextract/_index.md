---
title: "PdfFileEditor.TryExtract"
linktitle: "TryExtract"
articleTitle: "TryExtract"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Extracts pages from input file,saves as a new Pdf file."
type: docs
weight: 140
url: "/net/aspose.pdf.facades/pdffileeditor/tryextract/"
product_version: "26.9.0"
---
## TryExtract(string, int, int, string) {#tryextract}

Extracts pages from input file,saves as a new Pdf file.

The TryExtract method is like the Extract method, except the TryExtract 
 method does not throw an exception if the operation fails.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file path. |
| startPage | Int32 | Start page number. |
| endPage | Int32 | End page number. |
| outputFile | String | Output Pdf file path. |

### Return Value

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_1}

Extracts pages specified by number array, saves as a new PDF file.

The TryExtract method is like the Extract method, except the TryExtract 
 method does not throw an exception if the operation fails.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input file path. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputFile | String | Output file path. |

### Return Value

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract_2}

Extracts pages specified by number array, saves as a new Pdf file.

The TryExtract method is like the Extract method, except the TryExtract 
 method does not throw an exception if the operation fails.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputStream | Stream | Output file stream. |

### Return Value

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

