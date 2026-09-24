---
title: "PdfFileEditor.TryMakeNUp"
linktitle: "TryMakeNUp"
articleTitle: "TryMakeNUp"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Makes N-Up document from the firstInputFile to outputFile."
type: docs
weight: 290
url: "/net/aspose.pdf.facades/pdffileeditor/trymakenup/"
product_version: "26.9.0"
---
## TryMakeNUp(string, string, int, int) {#trymakenup}

Makes N-Up document from the firstInputFile to outputFile.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input pdf file path and name. |
| outputFile | string | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |

### Return Value

bool

true if operation was completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_1}

Makes N-Up document from the input stream and saves result into output stream.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, [PageSize](../../../aspose.pdf/pagesize/)) {#trymakenup_2}

Makes N-Up document from the first input stream to output stream.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_3}

Makes N-Up document from the two input PDF files to outputFile. 
 Each page of outputFile will contain two pages, one page is from the first input file 
 and another is from the second input file. The two pages are piled up horizontally.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | string | first input file. |
| secondInputFile | string | second input file. |
| outputFile | string | Output pdf file path and name. |

### Return Value

bool

true if operation was completed successfully; otherwise, false

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

Makes N-Up document from the two input PDF streams to outputStream.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | first input stream. |
| secondInputStream | Stream | second input stream. |
| outputStream | Stream | Output pdf stream. |

### Return Value

bool

true if operation was completed successfully; otherwise, false

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_5}

Makes N-Up document from the multi input PDF files to outputFile. 
 Each page of outputFile will contain multi pages, which are combination with pages 
 in the input files of the same page number. The multi pages piled up horizontally 
 if isSidewise is true and piled up vertically if isSidewise is false.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | string[] | Input Pdf files. |
| outputFile | string | Output pdf file path and name. |
| isSidewise | bool | Piled up way, true for horizontally and false for vertically. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_6}

Makes N-Up document from the multi input PDF streams to outputStream.
 Each page of outputStream will contain multi pages, which are combination with pages 
 in the input streams of the same page number. The multi-pages piled up horizontally 
 if isSidewise is true and piled up vertically if isSidewise is false.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | Input Pdf streams. |
| outputStream | Stream | Output pdf stream. |
| isSidewise | bool | Piled up way, true for horizontally and false for vertically. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, [PageSize](../../../aspose.pdf/pagesize/)) {#trymakenup_7}

Makes N-Up document from the input file to outputFile.

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp 
 method does not throw an exception if the operation fails.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input pdf file path and name. |
| outputFile | string | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

