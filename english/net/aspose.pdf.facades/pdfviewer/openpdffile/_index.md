---
title: "PdfViewer.OpenPdfFile"
linktitle: "OpenPdfFile"
articleTitle: "OpenPdfFile"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Opens a Pdf file, but does not actually decode the pages of the Pdf file."
type: docs
weight: 260
url: "/net/aspose.pdf.facades/pdfviewer/openpdffile/"
product_version: "26.9.0"
---
## OpenPdfFile(string) {#openpdffile}

> **Deprecated.** Use BindPdf instead of this method.

Opens a Pdf file, but does not actually decode the pages of the Pdf file.

```csharp
public void OpenPdfFile(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | string | The path of Pdf file. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.OpenPdfFile(@"d:\test.pdf");
 viewer.ClosePdfFile();
 
 [VisualBasic]
 Dim viewer As PdfViewer = new PdfViewer()
 viewer.OpenPdfFile(@"d:\test.pdf")
 viewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## OpenPdfFile(Stream) {#openpdffile_1}

> **Deprecated.** Use BindPdf instead of this method.

Opens a Pdf file stream. But does not actually decode the pages of the Pdf file.

```csharp
public void OpenPdfFile(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf stream to be opened. |

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.OpenPdfFile(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
 viewer.ClosePdfFile();
 
 [VisualBasic]
 Dim viewer As PdfViewer = new PdfViewer()
 viewer.OpenPdfFile(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
 viewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

