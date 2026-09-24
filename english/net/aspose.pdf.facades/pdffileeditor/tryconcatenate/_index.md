---
title: "PdfFileEditor.TryConcatenate"
linktitle: "TryConcatenate"
articleTitle: "TryConcatenate"
second_title: "Aspose.PDF for .NET"
description: "Concatenates two files."
type: docs
weight: 20
url: "/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/"
product_version: "26.9.0"
---
## TryConcatenate(string, string, string) {#tryconcatenate}

Concatenates two files.

The TryConcatenate method is like the Concatenate method, except the TryConcatenate 
 method does not throw an exception if the operation fails.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | string | First file to concatenate. |
| secInputFile | string | Second file to concatenate. |
| outputFile | string | Output file. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], [Document](../../../aspose.pdf/document/)) {#tryconcatenate_1}

Concatenates documents.

The TryConcatenate method is like the Concatenate method, 
 except the TryConcatenate method does not throw an exception if the operation fails.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| src | Document[] | Array of source documents. |
| dest | Document | Destination document. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_2}

Concatenates files into one file.

The TryConcatenate method is like the Concatenate method, 
 except the TryConcatenate method does not throw an exception if the operation fails.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | string[] | Array of files to concatenate. |
| outputFile | string | Name of output file. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_3}

Concatenates files

The TryConcatenate method is like the Concatenate method, 
 except the TryConcatenate method does not throw an exception if the operation fails.

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Array of streams to be concatenated. |
| outputStream | Stream | Stream where result file will be stored. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.
 e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'.
 Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

The TryConcatenate method is like the Concatenate 
 method, except the TryConcatenate method does not throw an exception if the operation fails.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | string | First file. |
| secInputFile | string | Second file. |
| blankPageFile | string | PDF file with blank page. |
| outputFile | string | Result file. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_5}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.
 e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'.
 Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

The TryConcatenate method is like the Concatenate 
 method, except the TryConcatenate method does not throw an exception if the operation fails.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | The first Pdf Stream. |
| secInputStream | Stream | The second Pdf Stream. |
| blankPageStream | Stream | The Pdf Stream with blank page. |
| outputStream | Stream | Output Pdf Stream. |

### Return Value

bool

true if operation completed successfully; otherwise, false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

