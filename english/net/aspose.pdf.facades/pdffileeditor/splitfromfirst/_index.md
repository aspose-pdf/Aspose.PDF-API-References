---
title: "PdfFileEditor.SplitFromFirst"
linktitle: "SplitFromFirst"
articleTitle: "SplitFromFirst"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits Pdf file from first page to specified location,and saves the front part as a new file."
type: docs
weight: 610
url: "/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/"
product_version: "26.9.0"
---
## SplitFromFirst(string, int, string) {#splitfromfirst}

Splits Pdf file from first page to specified location,and saves the front part as a new file.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source Pdf file. |
| location | Int32 | The splitting point. |
| outputFile | String | Output Pdf file. |

### Return Value

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst_1}

Splits from start to specified location,and saves the front part in output Stream.

The streams are NOT closed after this operation.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | Int32 | The splitting point. |
| outputStream | Stream | Output file Stream. |

### Return Value

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

