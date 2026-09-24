---
title: "PdfFileEditor.TrySplitToEnd"
linktitle: "TrySplitToEnd"
articleTitle: "TrySplitToEnd"
second_title: "Aspose.PDF for .NET"
description: "Splits from location, and saves the rear part as a new file."
type: docs
weight: 190
url: "/net/aspose.pdf.facades/pdffileeditor/trysplittoend/"
product_version: "26.9.0"
---
## TrySplitToEnd(string, int, string) {#trysplittoend}

Splits from location, and saves the rear part as a new file.

The TrySplitToEnd method is like the SplitToEnd method, except the TrySplitToEnd 
 method does not throw an exception if the operation fails.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
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

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend_1}

Splits from specified location, and saves the rear part as a new file Stream.

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.
 The TrySplitToEnd method is like the SplitToEnd method, except the TrySplitToEnd 
 method does not throw an exception if the operation fails.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
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

