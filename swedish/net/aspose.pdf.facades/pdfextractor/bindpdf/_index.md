---
title: BindPdf
second_title: Aspose.PDF för .NET API Referens
description: Bind in PDF-fil.
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Bind in PDF-fil.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | PDF-fil att binda |

### Exempel

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Se även

* class [PdfExtractor](../../pdfextractor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfextractor)
* hopsättning [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Binder PDF-dokument från stream.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström som innehåller PDF-dokumentdata |

### Exempel

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Se även

* class [PdfExtractor](../../pdfextractor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfextractor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
