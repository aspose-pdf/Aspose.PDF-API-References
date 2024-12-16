---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor method. Makes NUp document from the firstInputFile to outputFile
type: docs
weight: 440
url: /net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Makes N-up document and stores result into HttpResponse object.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Path to source file. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | Page size in result file. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Makes N-up document and stores result into HttpResponse object.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream of source document. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | Page size in result file. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Makes N-up document and stores result into HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source file name. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Makes N-up document and stores result into HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream of input document. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| response | HttpResponse | HttpResponse where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Makes N-Up document from the firstInputFile to outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |

### Return Value

true if operation was completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Makes N-Up document from the input stream and saves result into output stream.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | Output pdf stream. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Makes N-Up document from the first input stream to output stream.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | Output pdf stream. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | first input file. |
| secondInputFile | String | second input file. |
| outputFile | String | Output pdf file path and name. |

### Return Value

true if operation was completed successfully; otherwise, false

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Makes N-Up document from the two input PDF streams to outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | first input stream. |
| secondInputStream | Stream | second input stream. |
| outputStream | Stream | Output pdf stream. |

### Return Value

true if operation was completed successfully; otherwise, false

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Input Pdf files. |
| outputFile | String | Output pdf file path and name. |
| isSidewise | Boolean | Piled up way, true for horizontally and false for vertically. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | Input Pdf streams. |
| outputStream | Stream | Output pdf stream. |
| isSidewise | Boolean | Piled up way, true for horizontally and false for vertically. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Makes N-Up document from the input file to outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| x | Int32 | Number of columns. |
| y | Int32 | Number of rows. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


