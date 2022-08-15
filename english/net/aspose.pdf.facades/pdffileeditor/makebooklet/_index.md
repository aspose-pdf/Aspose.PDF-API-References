---
title: MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Makes booklet from the input file to output file.
type: docs
weight: 300
url: /net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Makes booklet from the input file to output file.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Makes booklet from the InputStream to outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | output pdf stream. |

### Return Value

True if operation was succeeded.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Makes booklet from the inputFile to outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

True if operation is succeeded.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Makes booklet from the input stream and save result into output stream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input PDF stream. |
| outputStream | Stream | output pdf stream. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value

True if operation was succeeded.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Makes customized booklet from the firstInputFile to outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The input file. |
| outputFile | String | Output pdf file path and name. |
| leftPages | Int32[] | The left pages of the booklet. |
| rightPages | Int32[] | The right pages of the booklet. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Makes customized booklet from the firstInputStream to outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The input stream. |
| outputStream | Stream | output pdf stream. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Makes customized booklet from the firstInputFile to outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Makes booklet from the firstInputStream to outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

boolean - True for success, or false.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
