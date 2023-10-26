---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor method. Makes booklet from source file and stores result into HttpResponse objects
type: docs
weight: 460
url: /net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Makes booklet from source file and stores result into HttpResponse objects.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source file path. |
| pageSize | PageSize | Desired page size. |
| leftPages | Int32[] | Aray of page numbers to be placed in left. |
| rightPages | Int32[] | Array of page numbers to be placed in right. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Make booklet from PDF file and stores it into HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input document stream. |
| pageSize | PageSize | Desired page size. |
| leftPages | Int32[] | Array of page numbers which will be placed in left. |
| rightPages | Int32[] | Array of page numbers which will b eplaced in right. |
| response | HttpResponse | HttpResponse object. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Makes booklet from source file and stores result into HttpResponse objects.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source file path. |
| pageSize | PageSize | Desired page size in output file. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

True if operation is succeeded.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Makes booklet from source file and stores result into HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input document stream. |
| pageSize | PageSize | Desired page size in output file. |
| response | HttpResponse | Respose object where resut will be saved. |

### Return Value

true if booklet was built successfully.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Makes booklet from the input file to output file.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

Makes booklet from the InputStream to outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | output pdf stream. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

Makes booklet from the inputFile to outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

True if operation is succeeded.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Makes booklet from the input stream and save result into output stream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input PDF stream. |
| outputStream | Stream | output pdf stream. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

Makes customized booklet from the firstInputFile to outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The input file. |
| outputFile | String | Output pdf file path and name. |
| leftPages | Int32[] | The left pages of the booklet. |
| rightPages | Int32[] | The right pages of the booklet. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

Makes customized booklet from the firstInputStream to outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The input stream. |
| outputStream | Stream | output pdf stream. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

Makes customized booklet from the firstInputFile to outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The input file. |
| outputFile | String | Output pdf file path and name. |
| pageSize | PageSize | The page size of the output pdf file. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

Makes booklet from the firstInputStream to outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The input stream. |
| outputStream | Stream | output pdf stream. |
| pageSize | PageSize | The page size of the output pdf file. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


