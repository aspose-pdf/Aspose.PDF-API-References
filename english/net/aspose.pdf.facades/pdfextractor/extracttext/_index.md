---
title: "PdfExtractor.ExtractText"
linktitle: "ExtractText"
articleTitle: "ExtractText"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Extracts text from a Pdf document using Unicode encoding."
type: docs
weight: 30
url: "/net/aspose.pdf.facades/pdfextractor/extracttext/"
product_version: "26.9.0"
---
## ExtractText() {#extracttext}

Extracts text from a Pdf document using Unicode encoding.

```csharp
public void ExtractText()
```

## Examples

First example demonstrates how to extract all the text from PDF file.
 
 Second example demonstrates how to extract each page's text into one txt file.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractText(Encoding) {#extracttext_1}

Extracts text from a Pdf document using specified encoding.

```csharp
public void ExtractText(Encoding encoding)
```

| Parameter | Type | Description |
| --- | --- | --- |
| encoding | Encoding | The encoding of the extracted text. |

## Examples

First example demonstrates how to extract all the text from PDF file.
 
 Second example demonstrates how to extract each page's text into one txt file.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText(Encoding.Unicode);
extractor.GetText(@"D:\Text\text.txt");
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

