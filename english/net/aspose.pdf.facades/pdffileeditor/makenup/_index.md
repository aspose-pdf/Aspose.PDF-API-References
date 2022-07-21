---
title: MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Makes N-Up document from the firstInputFile to outputFile.
type: docs
weight: 340
url: /net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

Makes N-Up document from the firstInputFile to outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Makes N-Up document from the input stream and saves result into output stream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | Output pdf stream. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Makes N-Up document from the first input stream to output stream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | Output pdf stream. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

True if operation was succeeded.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | first input file. |
| secondInputFile | String | second input file. |
| outputFile | String | Output pdf file path and name. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Makes N-Up document from the two input PDF streams to outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | first input stream. |
| secondInputStream | Stream | second input stream. |
| outputStream | Stream | Output pdf stream. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Input Pdf files. |
| outputFile | String | Output pdf file path and name. |
| isSidewise | Boolean | Piled up way, true for horizontally and false for vertically. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | Input Pdf streams. |
| outputStream | Stream | Output pdf stream. |
| isSidewise | Boolean | Piled up way, true for horizontally and false for vertically. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

Makes N-Up document from the input file to outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

Makes N-up document and stores result into HttpResponse object.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream of source document. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | Page size in result file. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

Makes N-up document and stores result into HttpResponse object.

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Path to source file. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | Page size in result file. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

Makes N-up document and stores result into HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source file name. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

Makes N-up document and stores result into HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream of input document. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| response | HttpResponse | HttpResponse where result will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
