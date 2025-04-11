---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metod. Binda inmatad PDF-fil
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Binda inmatad PDF-fil.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | PDF-fil att binda |

## Exempel

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Binder PDF-dokument från ström.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Ström som innehåller PDF-dokumentdata |

## Exempel

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)