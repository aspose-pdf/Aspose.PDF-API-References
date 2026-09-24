---
title: "PdfFileEditor.SplitToEnd"
linktitle: "SplitToEnd"
articleTitle: "SplitToEnd"
second_title: "Aspose.PDF for .NET"
description: "Splits from location, and saves the rear part as a new file."
type: docs
weight: 630
url: "/net/aspose.pdf.facades/pdffileeditor/splittoend/"
product_version: "26.9.0"
---
## SplitToEnd(string, int, string) {#splittoend}

Splits from location, and saves the rear part as a new file.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Source Pdf file. |
| location | int | The splitting position. |
| outputFile | string | Output Pdf file path. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend_1}

Splits from specified location, and saves the rear part as a new file Stream.

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | int | The splitting position. |
| outputStream | Stream | Output Pdf file Stream. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

