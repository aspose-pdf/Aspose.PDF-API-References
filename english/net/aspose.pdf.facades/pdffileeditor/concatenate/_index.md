---
title: "PdfFileEditor.Concatenate"
linktitle: "Concatenate"
articleTitle: "Concatenate"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Concatenates two files."
type: docs
weight: 400
url: "/net/aspose.pdf.facades/pdffileeditor/concatenate/"
product_version: "26.9.0"
---
## Concatenate(string, string, string) {#concatenate}

Concatenates two files.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | First file to concatenate. |
| secInputFile | String | Second file to concatenate. |
| outputFile | String | Output file. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatenates two files.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | Stream of first file. |
| secInputStream | Stream | Stream of second file. |
| outputStream | Stream | Stream where result file will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], [Document](../../../aspose.pdf/document/)) {#concatenate_2}

Concatenates documents.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| src | Document[] | Array of source documents. |
| dest | Document | Destination document. |

### Return Value

True if concatenation is successful.

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_3}

Concatenates files into one file.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Array of files to concatenate. |
| outputFile | String | Name of output file. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_4}

Concatenates files

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Array of streams to be concatenated. |
| outputStream | Stream | Stream where result file will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.
 e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'.
 Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | First file. |
| secInputFile | String | Second file. |
| blankPageFile | String | PDF file with blank page. |
| outputFile | String | Result file. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_6}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.
 e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'.
 Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | The first Pdf Stream. |
| secInputStream | Stream | The second Pdf Stream. |
| blankPageStream | Stream | The Pdf Stream with blank page. |
| outputStream | Stream | Output Pdf Stream. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

