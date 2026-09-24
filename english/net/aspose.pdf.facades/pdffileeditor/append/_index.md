---
title: "PdfFileEditor.Append"
linktitle: "Append"
articleTitle: "Append"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams..."
type: docs
weight: 470
url: "/net/aspose.pdf.facades/pdffileeditor/append/"
product_version: "26.9.0"
---
## Append(Stream, Stream[], int, int, Stream) {#append}

Appends pages, which are chosen from array of documents in portStreams.
 The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Pdf stream. |
| portStreams | Stream[] | Documents to copy pages from. |
| startPage | int | Page starts in portStreams documents. |
| endPage | int | Page ends in portStreams documents . |
| outputStream | Stream | Output Pdf stream. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_1}

Appends pages, which are chosen from portFiles documents. 
 The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input Pdf file. |
| portFiles | string[] | Documents to copy pages from. |
| startPage | int | Page starts in portFiles documents. |
| endPage | int | Page ends in portFiles documents . |
| outputFile | string | Output Pdf document. |

### Return Value

bool

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input Pdf file. |
| portFile | string | Pages from Pdf file. |
| startPage | int | Page starts in portFile. |
| endPage | int | Page ends in portFile. |
| outputFile | string | Output Pdf document. |

### Return Value

bool

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append_3}

Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| portStream | Stream | Pages from Pdf file Stream. |
| startPage | int | Page starts in portFile Stream. |
| endPage | int | Page ends in portFile Stream. |
| outputStream | Stream | Output Pdf file Stream. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

