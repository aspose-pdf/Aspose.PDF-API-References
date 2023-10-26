---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor method. Bind input PDF file
type: docs
weight: 100
url: /net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Bind input PDF file.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | PDF fiel to bind |

## Examples

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Binds PDF document from stream.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream containing PDF document data |

## Examples

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


