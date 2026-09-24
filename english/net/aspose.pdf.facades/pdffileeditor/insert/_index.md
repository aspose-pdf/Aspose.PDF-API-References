---
title: "PdfFileEditor.Insert"
linktitle: "Insert"
articleTitle: "Insert"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Inserts pages from an other file into the Pdf file at a position."
type: docs
weight: 510
url: "/net/aspose.pdf.facades/pdffileeditor/insert/"
product_version: "26.9.0"
---
## Insert(string, int, string, int, int, string) {#insert}

Inserts pages from an other file into the Pdf file at a position.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input Pdf file. |
| insertLocation | int | Position in input file. |
| portFile | string | The porting Pdf file. |
| startPage | int | Start position in portFile. |
| endPage | int | End position in portFile. |
| outputFile | string | Output Pdf file. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert_1}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | Stream | Stream of Pdf file for pages. |
| startPage | int | From which page to start. |
| endPage | int | To which page to end. |
| outputStream | Stream | Output Stream. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_2}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Input Pdf file. |
| insertLocation | int | Insert position in input file. |
| portFile | string | Pages from the Pdf file. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputFile | string | Output Pdf file. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_3}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | Stream | Stream of Pdf file for pages. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputStream | Stream | Output Stream. |

### Return Value

bool

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

