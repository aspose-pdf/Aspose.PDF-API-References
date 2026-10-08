---
title: "PdfFileEditor.SplitToEnd"
linktitle: "SplitToEnd"
articleTitle: "SplitToEnd"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits from location, and saves the rear part as a new file."
type: docs
weight: 630
url: "/net/aspose.pdf.facades/pdffileeditor/splittoend/"
product_version: "26.9"
---
## SplitToEnd(string, int, string) {#splittoend}

Splits from location, and saves the rear part as a new file.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source Pdf file. |
| location | Int32 | The splitting position. |
| outputFile | String | Output Pdf file path. |

### Return Value

True for success, or false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend_1}

Splits from specified location, and saves the rear part as a new file Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | Int32 | The splitting position. |
| outputStream | Stream | Output Pdf file Stream. |

### Return Value

True for success, or false.

## Remarks

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

