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
| inputFile | String | Source Pdf file. |
| location | Int32 | The splitting point. |
| outputFile | String | Output Pdf file. |

### Return Value

True for success, or false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

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
| location | Int32 | The splitting point. |
| outputStream | Stream | Output file Stream. |

### Return Value

True for success, or false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

