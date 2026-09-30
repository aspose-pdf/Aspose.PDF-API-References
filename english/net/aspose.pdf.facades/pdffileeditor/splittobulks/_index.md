---
title: "PdfFileEditor.SplitToBulks"
linktitle: "SplitToBulks"
articleTitle: "SplitToBulks"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits the Pdf file into several documents.The documents can be single-page or multi-pages."
type: docs
weight: 850
url: "/net/aspose.pdf.facades/pdffileeditor/splittobulks/"
product_version: "26.9.0"
---
## SplitToBulks(string, int[][]) {#splittobulks}

Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input PDF file. |
| numberOfPage | Int32[][] | Array which contains array of double elements, which is start and end pages of document. |

### Return Value

Output PDF streams, each stream buffers a PDF document.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks_1}

Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input PDF stream. |
| numberOfPage | Int32[][] | The start page and the end page of each document. |

### Return Value

Output PDF streams, each stream buffers a PDF document.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

