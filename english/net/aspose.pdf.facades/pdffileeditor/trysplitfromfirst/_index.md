---
title: "PdfFileEditor.TrySplitFromFirst"
linktitle: "TrySplitFromFirst"
articleTitle: "TrySplitFromFirst"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits Pdf file from first page to specified location,and saves the front part as a new file."
type: docs
weight: 170
url: "/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/"
product_version: "26.9.0"
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst}

Splits Pdf file from first page to specified location,and saves the front part as a new file.

The TrySplitFromFirst method is like the SplitFromFirst 
 method, except the TrySplitFromFirst method does not throw an exception if the operation fails.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | string | Source Pdf file. |
| location | int | The splitting point. |
| outputFile | string | Output Pdf file. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst_1}

Splits from start to specified location,and saves the front part in output Stream.

The streams are NOT closed after this operation.
 The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst 
 method does not throw an exception if the operation fails.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | int | The splitting point. |
| outputStream | Stream | Output file Stream. |

### Return Value

bool

True for success, or false.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

